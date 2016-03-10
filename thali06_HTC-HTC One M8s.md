#### Test 61362366b6c9a6f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  970): Killing 5180:com.google.android.setupwizard/u0a77 (adj 15): empty #18
--------- beginning of main
D/Process (  970): killProcessQuiet, pid=5180
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5180
I/ActivityManager(  970): Waited long enough for: ServiceRecord{1f0d986a u0 com.htc.club/com.mcrm.autonotification.NotificationService}
I/ConfigFetchService( 4218): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/GAV2    ( 5237): Thread[GAThread,5,main]: No campaign data found.
D/PMS     (  970): acquireWL(259292a7): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4218 10024 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4218): launchTask
D/PMS     (  970): releaseWL(2cebc8e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
D/PMS     (  970): acquireWL(3c418354): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4218): Module APK com.google.android.play.games already loaded
D/PMS     (  970): releaseWL(3c418354): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b +
I/Prism.WidgetManager( 1537): onLoadItems() +
I/PeopleContactsSync( 4218): CP2 sync disabled
D/Vision  ( 4218): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4218, uid=10024, userID:0
D/Vision  ( 4218): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4218): No vision deps
V/ConfigFetchTask( 4218): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5644 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/GoogleURLConnFactory( 4218): Using platform SSLCertificateSocketFactory
D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4218): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4218): [NET] android_getaddrinfo_proxy+
D/libc    ( 4218): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4218): [NET] android_getaddrinfo_proxy-, NODATA
W/ConfigFetchTask( 4218): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 4218): fetch service done; releasing wakelock
D/PMS     (  970): releaseWL(259292a7): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4218): stopping self
E/cutils-trace( 5634): Error opening trace file: Permission denied (13)
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
D/CustomizationManager( 5634): ====startRecUseTime====
D/htc.customization.log.level( 5634):  is 
W/CustomizationLogLevel( 5634): Level value is invalid, use default level 2
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
W/BaseAppContext( 4218): Using Auth Proxy for data requests.
D/CustomizationManager( 5634):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5634): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5634): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5634): Parsing tag category name = system
I/CustomizationCIDLoader( 5634): Parsing tag category name = application
I/CustomizationCIDLoader( 5634): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5634): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5634): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5634): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5634): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5634): add string-array item, value = 42507
I/CustomizationCIDLoader( 5634): add string-array item, value = 21902
I/CustomizationCIDLoader( 5634): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5634): add string-array item, value = 23420
I/CustomizationCIDLoader( 5634): add string-array item, value = 22299
I/CustomizationCIDLoader( 5634): add string-array item, value = 24002
I/CustomizationCIDLoader( 5634): add string-array item, value = 23210
I/CustomizationCIDLoader( 5634): add string-array item, value = 23205
I/CustomizationCIDLoader( 5634): add string-array item, value = 23806
I/CustomizationCIDLoader( 5634): add string-array item, value = 23430
I/CustomizationCIDLoader( 5634): add string-array item, value = 23408
I/CustomizationCIDLoader( 5634): add string-array item, value = 27205
I/CustomizationCIDLoader( 5634): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5634): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5634):  Read CID file spent 0.089 (s)
D/CustomizationManager( 5634):  All configurations done spent 0.089 (s)
W/asset   ( 1537): Copying FileAsset 0x556679df80 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5634 on display 0
D/PMS     (  970): acquireHCC(2dd80c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(a0a81f9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
W/asset   (  970): Copying FileAsset 0x5566b517a0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  970): acquireWL(2e79e8ec): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/FeedHostManager( 1537): [onPause]
I/FeedProviderManager( 1537): onPause
I/FeedHostManager( 1537): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@286ea685
I/SocialFeedProvider( 1537): +onPause
I/SocialFeedProvider( 1537): -onPause
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/13
E/Prism.WidgetManager( 1537): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1537): onLoadItems() -
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b -
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5686 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/asset   ( 5686): Copying FileAsset 0xac0cf150 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1537): [trimMemory] 20
D/StatusBarManagerService(  970): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
D/PhoneApp( 1489): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1489): -- N1 =0
D/PhoneApp( 1489): -- N2 =0
D/PhoneApp( 1489): -- N3 =0
,I/WebViewFactory( 5686): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4218, uid=10024, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4218, uid=10024, userID:0
,I/CheckinService( 4218): Done disabling old GoogleServicesFramework version
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4218, uid=10024, userID:0
,I/GAv4    ( 5644): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5644):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5644):   adb logcat -s GAv4
,I/LibraryLoader( 5686): Time to load native libraries: 11 ms (timestamps 2585-2596)
,I/LibraryLoader( 5686): Expected native library version number "",actual native library version number "",
,W/GAv4    ( 5644): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5644): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,V/WebViewChromiumFactoryProvider( 5686): Binding Chromium to main looper Looper (main, tid 1) {2934b6bd}
,I/LibraryLoader( 5686): Expected native library version number "",actual native library version number "",
,W/GAv4    ( 5644): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/chromium( 5686): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/AnalyticsTrackerProxyImpl( 5644): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/BrowserStartupController( 5686): Initializing chromium process, singleProcess=true
,W/art     ( 5686): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5686): ApplicationContext is null in ApplicationStatus
,D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4218): Module APK com.google.android.play.games already loaded
,W/chromium( 5686): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 5686): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5686): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5686): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5686): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5686): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5686): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5686): Local Branch: 
I/Adreno-EGL( 5686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5686): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5686):                  d74aa161a12b9c6fc6332151
,D/VoldConnector(  970): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5644): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,W/System.err(  970): java.lang.Throwable: stack dump,
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3df7db52:true
,D/BluetoothAdapter( 5686): 939196857: getState() :  mService = null. Returning STATE_OFF
,D/PMS     (  970): acquireWL(17fef238): PARTIAL_WAKE_LOCK  AsyncService 0x1 5480 10167 null
,W/ResourcesManager( 5644): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/PMS     (  970): releaseWL(17fef238): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/ResourcesManager( 5644): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  970): acquireWL(931f76): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5480 10167 null
,D/PMS     (  970): releaseWL(931f76): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,V/JNIHelp ( 5644): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/art     ( 5686): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 5411): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive,
I/ActivityManager(  970): Killing 5295:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5295
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 ,
W/AwContents( 5686): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5686): CordovaWebView is running on device made by: HTC
,W/System  ( 5644): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5644): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  970): Recipient 5295,
,I/UpdateIcingCorporaServi( 5337): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/art     ( 5686): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5686): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/asset   ( 5337): Copying FileAsset 0x55664cbf30 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.,
,I/UpdateIcingCorporaServi( 5337): UpdateCorporaTask done [took 57 ms] updated apps [took 57 ms] 
,D/Process (  970): killProcessQuiet, pid=4797
I/ActivityManager(  970): Killing 4797:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 4797,
,W/chromium( 5686): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 5686): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5686): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@33d3f0e5, mServedView=org.apache.cordova.engine.SystemWebView{1ac187ba VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@f9da66b
I/InputMethodManagerService(  970): Disable input method client, pid=1537
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  970): Enable input method client, pid=5686
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +1s157ms
D/PMS     (  970): releaseWL(2e79e8ec): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 5686): Cannot call determinedVisibility() - never saw a connection for the pid: 5686
W/XT9_C   ( 1352): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1352): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1352): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1352): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/AutoSetting( 1449): service - handleMessage() stop self
D/AutoSetting( 1449): service - handleMessage() quit looper
D/AutoSetting( 1449): service - onDestroy() END
D/JsMessageQueue( 5686): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5686): JniHelper::setJavaVM(0xaaf638f8), pthread_self() = -1406552456
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5686): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c70000c added. We now have 1 listener(s)
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5686): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fe9f9d1 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5686): addListener: New listener added - the number of listeners is now 1
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5686): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 5686): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  970): releaseHCC(2dd80c0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  970): releaseHCC(a0a81f9): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5686): Initializing JXcore engine
,W/jxcore-log( 5686): JXcore engine is ready
,I/HtcModeClient( 3162): handler message = 4011,
E/HtcModeClient( 3162): Check connection and retry 7 times.
,W/jxcore-log( 5686): Starting JXcore engine
,W/jxcore-log( 5686): Platform android
W/jxcore-log( 5686): 
W/jxcore-log( 5686): Process ARCH arm
W/jxcore-log( 5686): 
,I/jxcore-log( 5686): JXcore Cordova bridge is ready!,
I/jxcore-log( 5686): 
W/jxcore-log( 5686): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5686): execute: REQUEST_ACCESS_COARSE_LOCATION,
,I/ActivityManager(  970): Killing 5048:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5048
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5048,
,D/Process (  970): killProcessQuiet, pid=5096,
I/ActivityManager(  970): Killing 5096:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5096
,I/ConfigService( 1913): onDestroy
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{1758874c u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{f86a92d u0 com.htc.musicenhancer/.EnhancerService},
,I/art     (  970): Explicit concurrent mark sweep GC freed 23738(1252KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.948ms total 134.520ms
,W/MediaManager( 4878): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  970): killProcessQuiet, pid=4693,
I/ActivityManager(  970): Killing 4693:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  970): Recipient 4693
,D/Process (  970): killProcessQuiet, pid=5205
I/ActivityManager(  970): Killing 5205:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5205
,I/HtcModeClient( 3162): handler message = 4011
,E/HtcModeClient( 3162): Check connection and retry 8 times.
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
V/io.jxcore.node.JXcoreExtension( 5686): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 5686): WARN testUtils BLE multiple advertisement issue: null,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO testUtils Toggling radios to: true,
I/jxcore-log( 5686): 
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  970): checking for enable restriction...
D/BluetoothManagerService(  970): checkBTEasState, ret=true
I/BluetoothManagerService(  970): isBluetoothRestricted(): false
D/BluetoothManagerService(  970): enable(): region ID = 6
D/BluetoothManagerService(  970): enable():  mBluetooth =null mBinding = false
,W/Settings:Agent(  970): MONITOR_LOG
W/Settings:Agent(  970): name: bluetooth_on
W/Settings:Agent(  970): value: 1
W/Settings:Agent(  970): >> traceCallingStack()
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 4973,
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): ,	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 8(ms)
,D/BluetoothManagerService(  970): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  970): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 5686): Unit Test app is loaded
I/jxcore-log( 5686): 
,D/WifiManager( 5686): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,I/ActivityManager(  970): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5769 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/chromium( 5686): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66),
,D/WifiService(  970): setWifiEnabled: true pid=5686, uid=10366
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  970): isSprintWifiRestricted(): false
I/WifiService(  970): isMdmWifiRestricted(): false
,W/Settings:Agent(  970): MONITOR_LOG
W/Settings:Agent(  970): name: wifi_on
W/Settings:Agent(  970): value: 2
W/Settings:Agent(  970): >> traceCallingStack()
W/Settings:Agent(  970): Process.myPid(): 970
,W/Settings:Agent(  970): Process.myTid(): 1162
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403),
W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  970): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  970): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 5(ms)
,D/WifiManager( 5686): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiManager( 5686): reconnect: Base Package Name=com.test.thalitest, uid=10366
,E/WifiStateMachine(  970): handleMessage: E msg.what=131145
E/WifiStateMachine(  970): processMsg: InitialState
D/WifiController(  970): processMsg: ApStaDisabledState
D/WifiController(  970): transitionTo: destState=DeviceActiveState
D/WifiController(  970): handleMessage: new destination call exit/enter
D/WifiController(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  970): invokeExitMethods: ApStaDisabledState
D/WifiController(  970): moveTempStackToStateStack: i=1,j=1
D/WifiController(  970): moveTempStackToStateStack: i=0,j=2
D/WifiController(  970): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  970): invokeEnterMethods: StaEnabledState
D/WifiController(  970): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  970):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
,E/WifiStateMachine(  970):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131146
,E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
D/PMS     (  970): acquireWL(ccc2e75): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
E/WifiStateMachine(  970):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131083
E/WifiStateMachine(  970): processMsg: InitialState
E/WifiStateMachine(  970):  InitialState CMD_START_SUPPLICANT 0 0
,E/WifiStateMachine(  970): setting operational mode to 1
,D/WifiController(  970): handleMessage: X
,W/ResourcesManager( 5769): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5769): Adding HeadsetService
D/AdapterServiceConfig( 5769): Adding A2dpService
D/AdapterServiceConfig( 5769): Adding HidService
D/AdapterServiceConfig( 5769): Adding HealthService
D/AdapterServiceConfig( 5769): Adding PanService
D/AdapterServiceConfig( 5769): Adding GattService
,W/linker  ( 5769): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3797867b:true
D/BluetoothAdapterState( 5769): make
,I/BluetoothAdapterState( 5769): Entering OffState
,E/bt_osi_config( 5769): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothAdapterProperties( 5769): Address is:90:E7:C4:F6:69:77
D/BluetoothManagerService(  970): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  970): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  970): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  970): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  970): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 5769): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@37fb01b9
D/BluetoothAdapter( 5769): onBluetoothServiceUp done
D/BluetoothAdapter( 1223): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@36bef8ed
D/BluetoothAdapter( 1223): onBluetoothServiceUp done
,D/BluetoothAdapter( 3501): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@259aabf3
D/BluetoothAdapter( 3501): onBluetoothServiceUp done
D/BluetoothAdapter( 1511): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3eae2ef1
D/BluetoothAdapter( 1511): onBluetoothServiceUp done
D/BluetoothAdapter( 1489): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3eee0f12
D/BluetoothAdapter( 1489): onBluetoothServiceUp done
D/BluetoothAdapter( 1824): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1aac2c3
,D/BluetoothAdapter( 1824): onBluetoothServiceUp done
,D/BluetoothAdapter( 5686): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@6281003
D/BluetoothAdapter( 5686): onBluetoothServiceUp done
D/BluetoothAdapter( 2354): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1ef1a74d
D/BluetoothAdapter( 2354): onBluetoothServiceUp done
D/BluetoothAdapter(  970): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@340e0f57
D/BluetoothAdapter(  970): onBluetoothServiceUp done
D/BluetoothManagerService(  970): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 5769): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5769): Setting state to 11
I/BluetoothAdapterState( 5769): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  970): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  970): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  970): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  970): Bluetooth State Change Intent: 10 -> 11
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 5769): make
V/BluetoothPbapReceiver( 5769): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5769): ***********state = 11
,D/BluetoothAdapterService( 5769): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5769): checkA2dpState: returning
D/BluetoothAdapterService( 5769): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 5769): checkHfpState: returning
I/BluetoothBondStateMachine( 5769): StableState(): Entering Off State
,D/NGFService( 3501): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothAdapterState( 5769): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothHeadset( 1223): Proxy object connected
D/BluetoothHeadset( 1489): Proxy object connected
D/BluetoothHeadset(  970): Proxy object connected
D/HeadsetService( 5769): Received start request. Starting profile...
D/HeadsetStateMachine( 5769): Version 1.5
D/HeadsetStateMachine( 5769): make
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5803 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/BluetoothAdapter(  970): 210149093: getState(). Returning 11
,D/HeadsetStateMachine( 5769): max_hf_connections = 2
,D/PMS     (  970): releaseWL(ccc2e75): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/HeadsetPhoneState( 5769): listenForPhoneState..for service and signal ,
D/BluetoothHeadset( 1489): Proxy object connected
,D/HeadsetDualPhoneStateListener_SLOT1( 5769): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 5769): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 5769): Enter Disconnected: -2, size: 0
I/QuickSettingMiniLite( 1223): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@33766322
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/HeadsetDualPhoneStateListener_SLOT1( 5769): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 5769): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 5769): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 5769): BTHF: set_current_device
,D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/BluetoothA2dp(  970): Proxy object connected
D/A2dpService( 5769): Received start request. Starting profile...
V/Avrcp   ( 5769): make
,D/BluetoothAdapter(  970): 210149093: getState(). Returning 11
,D/BluetoothHeadset( 1489): Proxy object connected
,E/RemoteController( 5769): Cannot set synchronization mode on an unregistered RemoteController
,D/A2dpStateMachine( 5769): make
,D/bt-btif ( 5769): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/Tethering(  970): interfaceAdded wlan0
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/A2dpService( 5769): setA2dpService(): set to: null
D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
D/BluetoothPhoneService( 1489): BluetoothHeadset onServiceConnected
D/Tethering(  970): interfaceAdded p2p0
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): p2p0 is not a tetherable iface, ignoring
D/Tethering(  970): interfaceLinkStateChanged p2p0, false
D/Tethering(  970): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
,D/A2dpStateMachine( 5769): Enter Disconnected: -2
,E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): acquireWL(37160537): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
,I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/HidService( 5769): Received start request. Starting profile...
,D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
D/TetherSettings( 5387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5387): Cust_ConnectToPC   : spcsc>false
D/        ( 5387): Cust_ConnectToPC   : IPT>true
D/        ( 5387): Cust_ConnectToPC   : Singel_USB>false
,D/HealthService( 5769): Received start request. Starting profile...,
,W/Settings( 5387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
E/SmartNS_Utility( 5387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5387): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/PanService( 5769): Received start request. Starting profile...
,W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5387): setISNotification,
,D/HtcBtWidget_BTWidgetProvider( 5803): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 5803): updateWidget(context) for widget: 
,D/PMS     (  970): releaseWL(37160537): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  970): updateNetworkEnabledLocked()
,V/NetworkPolicy(  970): updateNotificationsLocked()
,E/WifiStateMachine(  970): setWifiState: enabling
E/WifiStateMachine(  970): Supplicant start successful
D/WifiMonitor(  970): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  970): connecting to supplicant
D/WIFI_ICON( 1223): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiHW  (  970): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/BluetoothAdapter( 1489): 99948768: getState(). Returning 11
I/IntentController( 1223): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/PanService( 5769): HTC_CUSTOMIZATION_MHS_ENABLE = false,
D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
D/SmartNS_Utility( 5387): usb_cable_connect = 1
,D/SmartNS_Utility( 5387): usb_denied = 0,
,I/SmartNS_PSService( 5387): usb notificaiton:true,
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/BtGatt.DebugUtils( 5769): handleDebugAction() action=null
D/BtGatt.GattService( 5769): Received start request. Starting profile...
D/BtGatt.GattService( 5769): start()
D/BtGatt.AdvertiseManager( 5769): advertise manager created
,D/BluetoothAdapter( 1223): 50812644: getState(). Returning 11
I/QuickSettingMiniLite( 1223): updateLiteState:no connect device!
,D/BluetoothAdapterService( 5769): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2934b6bd
,I/ActionCombine( 5387): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5387): usb_cable_connect = 1,
D/SmartNS_Utility( 5387): usb_denied = 0
I/SmartNS_PSService( 5387): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1223): reapply : com.android.settings 1 36,
D/SmartNS_NSReceiver( 5387): Tethered state change:false isNSOpening:false
,I/HeadsetPhoneState( 5769): updateServiceState service = 0,roam = 0,
D/HeadsetPhoneState( 5769): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5769): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5769): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5769): Disconnected process message: 11, size: 0
I/QuickSettingWifi( 1223): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
,D/Process (  970): killProcessQuiet, pid=5534
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=5837 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
I/ActivityManager(  970): Killing 5534:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/BluetoothAdapterState( 5769): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 5769): btu_task pending for preload complete event
D/BluetoothAdapter( 1489): 99948768: getState(). Returning 11
W/BluetoothHeadset( 1489): Proxy not attached to service
D/wpa_supplicant( 5834): wpa_supplicant v2.3-devel-5.0.2,
,D/BluetoothHeadset( 1489): java.lang.Throwable
D/BluetoothHeadset( 1489): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1489): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1489): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1489): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1489): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1489): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1489): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1489): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1489): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1489): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/wpa_supplicant( 5834): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5834): random: Trying to read entropy from /dev/random
E/bt_vendor( 5769): get_bt_soc_type: Failed to get soc type
D/wpa_supplicant( 5834): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 5834): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 5834): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 5834): Successfully initialized wpa_supplicant
D/wpa_supplicant( 5834): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
,D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5834): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 5834): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5834): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5834): update_config=1
D/wpa_supplicant( 5834): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5834): device_name='Android_608e'
D/wpa_supplicant( 5834): manufacturer='HTC'
D/wpa_supplicant( 5834): model_name='HTC_PHONE'
D/wpa_supplicant( 5834): model_number='1234'
D/wpa_supplicant( 5834): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5834): p2p_oper_reg_class=126
D/wpa_supplicant( 5834): p2p_oper_channel=149
D/wpa_supplicant( 5834): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 5834): persistent_reconnect=1
D/wpa_supplicant( 5834): key_mgmt_offload=1
I/wpa_supplicant( 5834): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5834): nl80211: RFKILL status not available
D/wpa_supplicant( 5834): nl80211: Using driver-based roaming
D/wpa_supplicant( 5834): nl80211: TDLS supported
D/wpa_supplicant( 5834): nl80211: TDLS external setup
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:5
,D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5834): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0,x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5834): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5834): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5834): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 5834): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 5834): nl80211: Subscribe to mgmt frames with non-AP handle 0x5572df1fd0
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0104
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=040a
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=040b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=040c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=040d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=090a
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=090b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=090c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=090d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0409506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=7f506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0801
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=040e
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=06
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0a07
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0a11
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572df1fd0 match=0a1a
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5834): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5834): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 5834): htc_wext_command_init +
E/wpa_supplicant( 5834): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5834): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  970): interfaceLinkStateChanged p2p0, false
D/Tethering(  970): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceLinkStateChanged p2p0, false
D/Tethering(  970): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/qcom-bluetooth( 5861): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,I/qcom-bluetooth( 5867): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/qcom-bluetooth( 5868): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 5870): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5871): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5872): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5873): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/ActivityManager(  970): Recipient 5534
,D/WifiService(  970): Client connection lost with reason: 4
,I/RemoteViews( 1223): reapply : com.android.settings 1 36
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/BluetoothMasReceiver( 5769): Bluetooth STATE CHANGED to 11
,I/wpa_supplicant( 5834): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 5834):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5834):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5834):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5834): nl80211: Flush PMKIDs
D/wpa_supplicant( 5834): p2p0: State: DISCONNECTED -> INACTIVE
,V/BluetoothSapReceiver( 5769): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5769): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5769):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 5769): startService = false
,D/AuthorizationBluetoothService( 1913): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 5837): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 5837): updateWidget(context) for widget: 
,D/Process (  970): killProcessQuiet, pid=4945
I/ActivityManager(  970): Killing 4945:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/wpa_supplicant( 5834): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5834): TDLS: Driver uses external link setup
D/wpa_supplicant( 5834): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 5834): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5834): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5834): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5834): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5834): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5834): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5834): Using existing control interface directory.
D/wpa_supplicant( 5834): P2P: Add operating class 81
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
,D/wpa_supplicant( 5834): P2P: Own listen channel: 81:6
D/wpa_supplicant( 5834): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 5834): P2P: initialized
D/wpa_supplicant( 5834): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5834): P2P: cli_channels:
,D/wpa_supplicant( 5834): p2p0: Added interface p2p0
D/wpa_supplicant( 5834): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 5834): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 5834): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5834): disable_scan_offload=1
D/wpa_supplicant( 5834): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 5834): update_config=1
D/wpa_supplicant( 5834): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5834): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 5834): manufacturer='HTC'
D/wpa_supplicant( 5834): model_name='HTC One M8s'
D/wpa_supplicant( 5834): model_number='HTC One M8s'
,D/wpa_supplicant( 5834): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 5834): hs20=1
D/wpa_supplicant( 5834): interworking=1
D/wpa_supplicant( 5834): external_sim=1
D/wpa_supplicant( 5834): key_mgmt_offload=1
,I/qcom-bluetooth( 5876): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,I/qcom-bluetooth( 5877): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 5834): Priority group 690
D/wpa_supplicant( 5834):    id=0 ssid='NG700'
I/wpa_supplicant( 5834): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5834): nl80211: RFKILL status not available
,D/wpa_supplicant( 5834): nl80211: Using driver-based roaming
D/wpa_supplicant( 5834): nl80211: TDLS supported
D/wpa_supplicant( 5834): nl80211: TDLS external setup
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5834): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5834): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0,
I/ActivityManager(  970): Recipient 4945
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/MediaRouterService(  970): Client com.google.android.music (pid 4945): Died!
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0,
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5834): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5834): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5834): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5834): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5834): nl80211: Use separate P2P group interface (driver advertised support)
D/PMS     (  970): acquireWL(2cbbbdd3): PARTIAL_WAKE_LOCK  bluedroid_tim,er 0x1 5769 1002 null
D/wpa_supplicant( 5834): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5834): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5834): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 5834): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 5834): nl80211: Subscribe to mgmt frames with non-AP handle 0x5572e11100
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0104
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040a
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090a
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0409506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=7f506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0801
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040e
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=06
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a07
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a11
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a1a
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5834): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 5834): nl80211: Use separate P2P group interface
D/wpa_supplicant( 5834): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 5834): htc_wext_command_init +
I/wpa_supplicant( 5834): htc_wext_command_init -
I/wpa_supplicant( 5834): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 5834): Don't set 00 to countryID.conf
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5834): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5834): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 57240-63720 @ 2160 MHz 0 mBm
,D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5834): P2P: Add operating class 81
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5834): P2P: Update channel list
D/wpa_supplicant( 5834): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5834): P2P: cli_channels:
D/wpa_supplicant( 5834): p2p0: Updating hw mode
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5834): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5834): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5834): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  970): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  970): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  970): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/bt-btu  ( 5769): btu_task received preload complete event
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x001f
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x1487
D/bt-btm  ( 5769): btm_acl_device_down
D/PMS     (  970): acquireWL(23f84d10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): sendTetherStateChangedBroadcast 0, 0, 0
D/bt-btm  ( 5769): btm_acl_reset_paging
D/bt-btm  ( 5769): btm_acl_set_discing
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/TetherSettings( 5387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5387): Cust_ConnectToPC   : spcsc>false
D/        ( 5387): Cust_ConnectToPC   : IPT>true
D/        ( 5387): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5387): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  970): releaseWL(23f84d10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5387): setISNotification
D/SmartNS_Utility( 5387): usb_cable_connect = 1
D/SmartNS_Utility( 5387): usb_denied = 0
I/SmartNS_PSService( 5387): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_Utility( 5387): usb_cable_connect = 1
D/SmartNS_Utility( 5387): usb_denied = 0
I/SmartNS_PSService( 5387): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5387): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
I/bt-btm  ( 5769): btm_reset_complete
I/bt-btm  ( 5769): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5769): Start reading local supported commands,
,D/bt-btm  ( 5769): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 5769): BTM reads next extended features page (1)
,D/bt-btm  ( 5769): BTM reads next extended features page (2)
,D/bt-btm  ( 5769): BTM reached last extended features page (2)
D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
,I/bt-btm  ( 5769): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 5769): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01,
,D/bt-btm  ( 5769): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00,
D/bt-btm  ( 5769): btm_read_ble_wl_size 
,D/bt-btm  ( 5769): btm_read_white_list_size_complete ,
D/bt-btm  ( 5769): btm_get_ble_buffer_size 
,D/bt-btm  ( 5769): btm_read_ble_buf_size_complete ,
D/bt-btm  ( 5769): btm_read_ble_local_supported_states 
D/bt-btm  ( 5769): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5769): btm_read_ble_local_supported_features 
,D/bt-btm  ( 5769): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 5769): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5769): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5769): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5769): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5769): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5769): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 5769): BTM_SetInquiryMode
I/bt-btm  ( 5769): BTM_SetPageScanType
I/bt-btm  ( 5769): BTM_SetInquiryScanType
D/bt-btm  ( 5769): btm_decode_ext_features_page page: 1
W/bt-btm  ( 5769): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 5769): btm_decode_ext_features_page page: 2
W/bt-btm  ( 5769): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5769): BTM_BleLoadLocalKeys
D/bt-btm  ( 5769): BTM_BleLoadLocalKeys
I/bt-btm  ( 5769): BTM_Sec: application registered
E/bt-btm  ( 5769): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf90f4d5 
I/bt-btm  ( 5769): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 5769): SMP_Register state=0
E/bt-btm  ( 5769): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf90f4d5 
,I/bt-btm  ( 5769): BTM_Sec: application registered
D/bt-btm  ( 5769): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5769): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5769): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5769): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 5769): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5769): BTM_RegBusyLevelNotif
D/bt-btm  ( 5769): BTM_BleReadControllerFeatures,
I/bt-btm  ( 5769): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 5769): GATT_Register
D/bt-att  ( 5769): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 5769): allocated gatt_if=3
I/bt-att  ( 5769): GATT_StartIf gatt_if=3
D/bt-att  ( 5769): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5769): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 5769): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 5769): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 5769): BTM Register For VSEvents is successfully
D/bt-btm  ( 5769): BTM_BleGetVendorCapabilities
I/bt-btif ( 5769): HAL bt_hal_cbacks->adapter_properties_cb,
D/BluetoothAdapterProperties( 5769): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 5769): Calling BTA_HhEnable
D/bt-btm  ( 5769): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btm  ( 5769):  BTM_BleConfigPrivacy
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
,I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 5769): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 5769): BTM_AllocateSCN
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
,D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5769): BTM_AllocateSCN
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btm  ( 5769): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5769):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5769):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 5769): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 5769): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
,I/bt-btm  ( 5769):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5769):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 5769): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 5769): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
,I/bt-btm  ( 5769):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 5769): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 5769): A2D_AddRecord uuid: 110a
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
D/bt-btif ( 5769):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 5769): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_MceEnable
I/bt-btm  ( 5769): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5769):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5769):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5769):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5769): GATT_Register
D/bt-att  ( 5769): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5769): allocated gatt_if=4
I/bt-att  ( 5769): GATT_StartIf gatt_if=4
,D/bt-att  ( 5769): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5769): gatt_find_the_connected_bda found=0 found_idx=16
E/bt-btif ( 5769): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 5769): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5769): Address is:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 5769): Scan Mode:21
D/BluetoothAdapterProperties( 5769): Discoverable Timeout:120
I/bt-btif ( 5769): BTA_JvEnable
I/bt-btif ( 5769): BTA_JvRegisterL2cCback
I/bt-btm  ( 5769): BTM_ReadConnectability
I/bt-btm  ( 5769): BTM_ReadDiscoverability
I/bt-btm  ( 5769): BTM_SetDiscoverability
,I/bt-btm  ( 5769): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 5769): disc_mode 0002
D/bt-btm  ( 5769): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5769): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5769): BTM_SetConnectability
I/bt-btm  ( 5769): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5769): disc_mode 0002
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 5769): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 5769): BTM_SetDiscoverability
I/bt-btm  ( 5769): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5769): disc_mode 0000
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5769): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 5769): BTM_SetConnectability
I/bt-btm  ( 5769): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5769): disc_mode 0000
D/bt-btm  ( 5769): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 5769): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
I/bt-btm  ( 5769): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5769): bta_pan_co_init
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 5769): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5769):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5769):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btm  ( 5769): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5769):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5769): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5769):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = b0 74 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 5b 55 6d 63 65 96 9a 52 7d c1 ff 37 62 9b a8 25 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5769): Stopping oneshot timer
D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
,D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 5769): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
,D/bt-btif ( 5769): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5769): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5769): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 5769): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 5769): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5769): ScanMode =  21
D/BluetoothAdapterProperties( 5769): State =  11
I/bt-btif ( 5769): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5769): Setting state to 12
I/BluetoothAdapterState( 5769): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 5769): Discoverable Timeout:120
D/BluetoothManagerService(  970): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  970): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  970): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  970): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1489): onBluetoothStateChange: up=true
D/BluetoothHeadset(  970): onBluetoothStateChange: up=true
D/BluetoothA2dp(  970): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 5769): Entering On State
D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 55 ff 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 1d 64 4f 63 92 e9 ca ae 1d 3e 68 b6 ec 8d ca 01 
D/BluetoothHeadset( 1489): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1489): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  970): Bluetooth State Change Intent: 11 -> 12
,E/bt_mct  ( 5769): hci lib postload completed
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3501): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
D/NGFService( 3501): Bluetooth Adapter: ON
,D/BluetoothManagerService(  970): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  970): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  970): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 37 14 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = c3 a0 dd 99 6a ab d7 16 41 1e 2d 9e 7d 91 03 08 
V/BluetoothPbapReceiver( 5769): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5769): ***********state = 12
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
,I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/PMS     (  970): acquireWL(efa642f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5387 1000 null
D/bt-smp  ( 5769): smp_encrypt_data
I/wpa_supplicant( 5834): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 5834):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5834):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5834):  Initialization: WAPI:set Staues=1 
,D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5834): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5834): nl80211: Flush PMKIDs
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 00 07 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 87 27 b4 02 de 34 b3 d0 cf 69 f9 08 d7 9d 41 9d 
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 18 28 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = a7 00 90 4b 45 89 40 6a 48 4f 73 02 c3 ef bf 6a 
,V/BluetoothPbapService( 5769): Pbap Service onCreate
V/BluetoothPbapService( 5769): Starting PBAP service
D/BluetoothAdapter( 5769): 895397695: getState(). Returning 12
V/BluetoothPbapService( 5769): Handler(): got msg=1
V/BluetoothPbapService( 5769): Pbap Service startRfcommSocketListener
,D/HtcBtWidget_BTWidgetProvider( 5803): onBTStateChanged() for widget: 
,V/BluetoothPbapService( 5769): Pbap Service initSocket
D/HtcBtWidget_BTWidgetProvider( 5803): updateWidget(context) for widget: 
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = fb c6 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 24 74 55 33 49 88 60 7a 71 14 4a 88 54 10 64 63 
D/PMS     (  970): releaseWL(efa642f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  970): acquireWL(1c9173c5): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5387 1000 null
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/System.err(  970): java.lang.Throwable: stack dump,
W/System.err(  970): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3210ae28:true
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 1c 07 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 9d 84 df f5 6c 7e e3 43 84 1c c1 f8 77 3c dd 51 
W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btm  ( 5769): BTM_SetDiscoverability
I/bt-btm  ( 5769): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5769): disc_mode 0000
I/bt-btm  ( 5769): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5769): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5769): BTM_SetConnectability
I/bt-btm  ( 5769): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5769): disc_mode 0000
D/bt-btm  ( 5769): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5769): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 5769): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5769): BTA_JvCreateRecordByUser
I/bt-btif ( 5769): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5769):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 5769): Succeed to create listening socket 
V/BluetoothPbapService( 5769): Accepting socket connection...
D/BluetoothAdapter( 1223): 50812644: getState(). Returning 12
D/BluetoothAdapterProperties( 5769): Scan Mode:21
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 56 4d 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 87 29 9c 42 c8 5c 61 31 d9 51 93 c8 98 43 1e 80 
,D/BluetoothAdapter( 1223): 50812644: getState(). Returning 12
,D/BluetoothAdapter( 5387): 477102092: getState(). Returning 12
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1223): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
,I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 4f 58 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 5d a7 0e 2f 71 fe 82 f5 0c cb 71 b9 19 da 2e 59 
,D/BluetoothInputDevice( 5387): BluetoothInputDevice()
D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  970): Registered receivers: 7
D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 89 ee 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = d0 54 90 bb 1c e4 b9 e8 a0 b0 f8 a0 34 55 38 1a 
,D/BluetoothPan( 5387): BluetoothPan()
,D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  970): Registered receivers: 8
,D/BluetoothMap( 5387): Create BluetoothMap proxy object
,D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  970): Registered receivers: 9
E/BluetoothMap( 5387): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothSap( 5387): BluetoothSap() call bindService
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  970): Registered receivers: 10
,W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 97 8c 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = c4 dd 10 b7 c5 40 d3 d5 f5 fa 7a af c8 3c 07 28 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5769): Stopping oneshot timer
D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
,D/BluetoothPbap( 5387): BluetoothPbap()
,D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  970): Registered receivers: 11
D/BluetoothManagerService(  970): registerStateChangeCallback+
,D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  970): Registered receivers: 12
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
,I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 03 79 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 15 dc af 8b 21 07 12 89 fc 10 08 15 55 a3 a9 59 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
D/BluetoothHeadset( 5387): BluetoothHeadset()
W/bt-btm  ( 5769): Stopping oneshot timer
D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  970): registerStateChangeCallback+
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  970): Registered receivers: 13
,D/LocalBluetoothProfileManager( 5387): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5387): finishStartingService: stopping service
D/BluetoothA2dp( 5387): Proxy object connected
,D/A2dpProfile( 5387): Bluetooth service connected
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = b6 ad 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = da 4b 31 60 02 17 e0 d2 4c 5c 94 3c 36 40 7c 61 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5769): Stopping oneshot timer
D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 5387): 477102092: getState(). Returning 12
,D/BluetoothHeadset( 5387): Proxy object connected,
,D/HeadsetProfile( 5387): Bluetooth service connected
D/BluetoothAdapter( 5387): 477102092: getState(). Returning 12
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete,
D/PMS     (  970): releaseWL(1c9173c5): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/BluetoothInputDevice( 5387): Proxy object connected
D/bt-smp  ( 5769): smp_encrypt_data
W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 06 1e 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = 2c 19 da ea 95 bc 80 4f d0 13 c0 1d a5 56 c6 18 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
D/HidProfile( 5387): Bluetooth service connected
,W/bt-btm  ( 5769): Stopping oneshot timer
,D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 5387): 477102092: getState(). Returning 12
D/BluetoothPan( 5387): BluetoothPAN Proxy object connected
V/BluetoothPbapService( 5769): Pbap Service onBind
D/PanProfile( 5387): Bluetooth service connected
D/BluetoothPbap( 5387): Proxy object connected
D/PbapServerProfile( 5387): Bluetooth service connected
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
,I/bt-btm  ( 5769): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 5769):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/wpa_supplicant( 5834): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5834): TDLS: Driver uses external link setup
D/wpa_supplicant( 5834): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5834): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5834): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5834): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5834): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5834): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5834): EAP: EAP entering state DISABLED
I/BtOppRfcommListener( 5769): Accept thread started.
D/wpa_supplicant( 5834): Using existing control interface directory.
,D/BluetoothAdapter( 5769): 895397695: getState(). Returning 12
,I/wpa_supplicant( 5834): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 5834): Initial scan channel cmd: COUNTRY DE
D/BluetoothFtpService( 5769): ACTION_STATE_CHANGED: state: 12mHasStarted: true
I/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/BluetoothMasReceiver( 5769): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5769):  call MAP start service
,D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 5834): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5834): P2P: Add operating class 81
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5834): P2P: Add operating class 115
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5834): P2P: Add operating class 116
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5834): P2P: Add operating class 117
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5834): P2P: Update channel list
D/wpa_supplicant( 5834): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5834): P2P: cli_channels:
D/wpa_supplicant( 5834): p2p0: Updating hw mode
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 5834): Auto country group 1: ch36
D/wpa_supplicant( 5834): wlan0: Added interface wlan0
D/wpa_supplicant( 5834): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 5834): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5834): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 5834): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/BluetoothFtpService( 5769): htc sense version is 6.0
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5834): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 5834): nl80211: Regulatory domain change
D/wpa_supplicant( 5834):  * initiator=1
D/wpa_supplicant( 5834):  * type=0
,D/wpa_supplicant( 5834):  * alpha2=DE
D/wpa_supplicant( 5834): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5834): P2P: Add operating class 81
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5834): P2P: Add operating class 115
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5834): P2P: Add operating class 116
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5834): P2P: Add operating class 117
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5834): P2P: Update channel list
D/wpa_supplicant( 5834): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5834): P2P: cli_channels:
D/wpa_supplicant( 5834): p2p0: Updating hw mode
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 5769):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 5769): Run Accept thread
,E/BluetoothMasService( 5769): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 5769): Add permission for SmsProvider.
,V/BluetoothMasService( 5769): Starting MAS instances
,D/BluetoothAdapter( 5769): 895397695: getState(). Returning 12
,I/MailMessageReceiver( 5769): reg:com.android.bluetooth.btservice.AdapterApp@5f444a4 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@30c3620d
,I/MailManager( 5769): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@30c3620d
V/EmailUtils( 5769): Manager Instance is not NULL
,I/ActivityManager(  970): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5895 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/HtcAdjCursorFactory( 5895): Set CursorWindow size to: 4194304 KB, Tid: 5914
,D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
,D/Tethering(  970): interfaceLinkStateChanged p2p0, false
D/Tethering(  970): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/EmailUtils( 5769): ============NULL aList========
V/EmailUtils( 5769): <-getEmailAccountIdList,
V/BluetoothMasService( 5769): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 5769): 895397695: getState(). Returning 12
V/BluetoothMasService( 5769): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 5769): Manager Instance is not NULL
,D/EmailUtils( 5769): ============NULL aList========
V/EmailUtils( 5769): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5769): SapReceiver onReceive 
V/BluetoothSapReceiver( 5769): action = android.bluetooth.adapter.action.STATE_CHANGED,
V/BluetoothSapReceiver( 5769):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5769): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothMasService( 5769): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 5769): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1913): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-btm  ( 5769): BTM_AllocateSCN
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5769):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-btm  ( 5769): BTM_AllocateSCN
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5769):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  970): killProcessQuiet, pid=5237
I/ActivityManager(  970): Killing 5237:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  970): Recipient 5237
,D/wpa_supplicant( 5834): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_970-3\x00,
,E/WifiStateMachine(  970): transitionTo: destState=SupplicantStartingState,
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null,
E/WifiStateMachine(  970): invokeExitMethods: InitialState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=1
,E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  970): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131144
E/WifiStateMachine(  970): processMsg: SupplicantStartingState
E/WifiStateMachine(  970):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  970): deferMessage: msg=131144
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131085
E/WifiStateMachine(  970): processMsg: SupplicantStartingState
E/WifiStateMachine(  970):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  970): deferMessage: msg=131085
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131149
E/WifiStateMachine(  970): processMsg: SupplicantStartingState
E/WifiStateMachine(  970):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  970): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  970): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: SupplicantStartingState
,E/WifiStateMachine(  970):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
,E/WifiStateMachine(  970): processMsg: SupplicantStartingState
E/WifiStateMachine(  970):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState,
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147457
E/WifiStateMachine(  970): processMsg: SupplicantStartingState
E/WifiStateMachine(  970):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,E/WifiStateMachine(  970): Supplicant connection established
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 5834): set wifi ON
,E/WifiStateMachine(  970): setWifiState: enabled,
,V/BluetoothSapService( 5769): Sap Service onCreate,
V/BluetoothSapService( 5769): initBinder
V/BluetoothSapService( 5769): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@3d830710
V/BluetoothSapService( 5769): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@38f99c0e
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/WIFI_ICON( 1223): updateWifiState: WIFI_STATE_CHANGED enabled
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET update_config 1'
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5834): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 5834): update_config=1
D/wpa_supplicant( 5834): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
I/IntentController( 1223): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
V/BluetoothSapService( 5769): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5769): state: 12
D/WifiConfigStore(  970): Loading config and enabling all networks 
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 5834): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 5834): wpa_supplicant_ctrl_iface_list_networks: return size = 47
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/SapServerProfile( 5387): Bluetooth service connected
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 5834): Do not allow key_data field to be exposed
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='proto'
V/BluetoothSapService( 5769): Starting SAP server process
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK, 0 key_mgmt"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/HtcWiFiWidget_WiFiWidgetProvider( 5837): onWiFiStateChanged() for widget: 
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
V/BluetoothSapService( 5769): SAP Service startRfcommListenerThread
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/HtcWiFiWidget_WiFiWidgetProvider( 5837): updateWidget(context) for widget: 
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
V/BluetoothSapService( 5769): Sap Service initRfcommSocket
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,W/BluetoothAdapter( 5769): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 5769): Write Extended Inquiry Response to controller
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 5769):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothSapService( 5769): Succeed to create listening socket 
V/BluetoothSapService( 5769): Accepting socket connection...
,E/WifiConfigStore(  970): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 5834): device_name='m8qlul_htc_europe'
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 5834): manufacturer='HTC'
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 5834): model_name='HTC One M8s'
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 5834): model_number='HTC One M8s'
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 5834): config_methods='physical_display virtual_push_button'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  970): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  970): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  970): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 5834): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  970): Setting external_sim to 1
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/WifiP2pService(  970): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET external_sim 1'
D/WifiP2pService(  970): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5834): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 5834): external_sim=1
D/WifiStateMachine(  970): Setting OUI to DA-A1-19
I/WifiNative-HAL(  970): startHal
,E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f75b7b360,
I/WifiNative-HAL(  970): Could not start hal
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  970): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  970): Driverstarted State enter
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
,E/WifiStateMachine(  970): DriverStartedState call setCountryCode()
E/WifiStateMachine(  970): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
I/QuickSettingWifi( 1223): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192,
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/WifiDataStallTracker(  970): setDhcpActive: false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 5834): wlan0: Control interface command 'STATUS'
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state DriverStartedState suppState:UninitializedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 5834): SET_SCREEN_ON:On
I/wpa_supplicant( 5834): htc_wext_set_keepalive +
I/wpa_supplicant( 5834): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 5834): getPrivFuncNum +	
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
I/wpa_supplicant( 5834): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING - ret = 0
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
I/WifiNative-HAL(  970): startHal
E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f75b7b2f0
I/WifiNative-HAL(  970): Could not start hal
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
D/WifiP2pService(  970): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 5834): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
E/WifiStateMachine(  970): Driverstarted State enter done
E/WifiStateMachine(  970): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  970): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=w,lan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/wpa_supplicant( 5834): wlan0: Setting scan request: 0.000000 sec
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
I/wpa_supplicant( 5834): wpa_supplicant_scan enter
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 5834): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 5834): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 5834): WPS: Building WPS IE for Probe Request
D/WifiP2pService(  970): P2pEnablingState
D/wpa_supplicant( 5834): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 5834): WPS:  * Request Type
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5834): WPS:  * Config Methods (4288)
D/wpa_supplicant( 5834): WPS:  * UUID-E
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5834): WPS:  * Primary Device Type
D/wpa_supplicant( 5834): WPS:  * RF Bands (3)
D/wpa_supplicant( 5834): WPS:  * Association State
D/wpa_supplicant( 5834): WPS:  * Configuration Error (0)
D/wpa_supplicant( 5834): WPS:  * Device Password ID (0)
D/wpa_supplicant( 5834): WPS:  * Manufacturer
D/wpa_supplicant( 5834): WPS:  * Model Name
D/wpa_supplicant( 5834): WPS:  * Model Number
D/wpa_supplicant( 5834): WPS:  * Device Name
D/wpa_supplicant( 5834): WPS:  * Version2 (0x20)
D/wpa_supplicant( 5834): P2P: * P2P IE header
D/wpa_supplicant( 5834): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 5834): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 5834): wlan0: Add radio work 'scan'@0x5572e160f0
D/wpa_supplicant( 5834): wlan0: First radio work item in the queue - schedule start immediately
,D/wpa_supplicant( 5834): wlan0: Starting radio work 'scan'@0x5572e160f0 after 0.000048 second wait
D/wpa_supplicant( 5834): wlan0: nl80211: scan request
D/wpa_supplicant( 5834): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 5834): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 5834): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 5834): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 5834): wlan0: Own scan request started a scan in 0.000095 seconds
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-SCAN-STARTED 
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiScanningService(  970): SCAN_AVAILABLE : 3
E/WifiStateMachine(  970): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
D/RttService(  970): SCAN_AVAILABLE : 3
D/WifiScanningService(  970): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  970): startHal
D/RttService(  970): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f738e5520
I/WifiNative-HAL(  970): Could not start hal
D/WifiMonitor(  970): startMonitoring(p2p0) with mConnected = true
E/WifiScanningService(  970): could not start HAL
D/WifiP2pService(  970): P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiP2pService(  970): P2p socket connection successful
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiP2pService(  970): P2pEnabledState
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  970): sending p2p connection changed broadcast
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131144
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131085
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/A2dpService( 5769): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@36f9843c
E/WifiStateMachine(  970):  DisconnectedState !CMD_START_DRIVER 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_START_DRIVER 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/A2dpSinkService( 5769): getA2dpSinkService(): service is NULL
E/WifiStateMachine(  970):  DriverStartedState !CMD_START_DRIVER 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131323
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !what:131323 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !what:131323 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !what:131323 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !what:131323 0 0
E/WifiStateMachine(  970): processMsg: D,efaultState
E/WifiStateMachine(  970):  DefaultState !what:131323 0 0
E/WifiStateMachine(  970): setOperatorSSID enter
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131104
W/WifiHW  (  970): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 5834): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5834): p2p0: Control interface command 'SET persistent_reconnect 1'
D/WifiDisplayController(  970): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/wpa_supplicant( 5834): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5834): persistent_reconnect=1
D/wpa_supplicant( 5834): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5834): P2P: New SSID postfix: -Android_608e
D/WifiDisplayController(  970): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 5834): P2P: Set Operating channel: reg_class 126 channel 149
D/WifiDisplayController(  970): mWfdEnabled :false, networkInfo.isConnected() :false
E/WifiStateMachine(  970):  DisconnectedState !what:131104 0 0
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !what:131104 0 0
W/Settings(  970): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 5834): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  970): handleMessage: X
W/WifiHW  (  970): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  970): handleMessage: E msg.what=131162
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 5834): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 5834): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 5834): device_name='Android_608e'
E/WifiStateMachine(  970):  DisconnectedState !CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
V/AudioService(  970): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  970):     Client/Owner: Client
V/AudioService(  970):     GroupId: 
V/AudioService(  970):     Passphrase: 
V/AudioService(  970):     SessionId: 0
V/AudioService(  970):     IP Address: }
D/HtcEffectManagerBase(  970): onEventChanged id=5 status=false
D/HtcEffectManager(  970): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=f,alse mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  970): convertEffect before=902
D/HtcEffectManager(  970): convertEffect after=902
W/WifiHW  (  970): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
E/WifiStateMachine(  970):  ConnectModeState !CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 5834): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 5834): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 5834): p2p_ssid_postfix='-Android_608e'
E/WifiStateMachine(  970):  DriverStartedState !CMD_SET_FREQUENCY_BAND 0 0
D/wpa_supplicant( 5834): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  970): set frequency band 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 5834): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 5834): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 5834): SETBAND: 0
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 5834): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5834): P2P: Add operating class 81
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5834): P2P: Add operating class 115
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5834): P2P: Add operating class 116
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5834): P2P: Add operating class 117
D/wpa_supplicant( 5834): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5834): P2P: Update channel list
D/wpa_supplicant( 5834): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5834): P2P: cli_channels:
D/wpa_supplicant( 5834): p2p0: Updating hw mode
D/wpa_supplicant( 5834): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5834): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5834): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5834): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5834): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  970): did set frequency band 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 5834): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5834): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 5834): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5834): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  970): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 5834): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 5834): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 5834): Single channel concurrency preference: sta
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/WifiNative-HAL(  970): p2pGetDeviceAddress
D/wpa_supplicant( 5834): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5834): Pending scan scheduled - reject new request
W/WifiHW  (  970): QCOM Debug wifi_send_command "STATUS"
E/WifiStateMachine(  970): done set frequency band 0
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  970): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
D/WifiP2pService(  970): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  970): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 5834): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 5834): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 5834): P2P: Stopping find
D/wpa_supplicant( 5834): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5834): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5834): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 5834): P2P: Stopping find
D/wpa_supplicant( 5834): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5834): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5834): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  970): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 5834): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 5834): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  970): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 5834): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiDisplayController(  970): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  970):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  970):  primary type: 10-0050F204-5
D/WifiDisplayController(  970):  secondary type: null
D/WifiDisplayController(  970):  wps: 0
D/WifiDisplayController(  970):  grpcapab: 0
D/WifiDisplayController(  970):  devcapab: 0
D/WifiDisplayController(  970):  status: 3
D/WifiDisplayController(  970):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  970):  WFD CtrlPort: 0
D/WifiDisplayController(  970):  WFD MaxThroughput: 0
D/wpa_supplicant( 5834): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  970): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 5834): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 5834): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  970): sending p2p persistent groups changed broadcast
D/WifiP2pService(  970): InactiveState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiStateMachine(  970): Wifi band: 0, ScanBroadCastCounter: 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131127
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131129
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 5834): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 5834): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=4 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=82212  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=82213  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=82213  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info0x
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 1
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=82217  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 2
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=143371
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  970): processMsg: DriverStartedState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  DriverStartedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 5834): EAPOL: disable timer tick
,D/wpa_supplicant( 5834): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 5834): wlan0: nl80211: New scan results available
D/wpa_supplicant( 5834): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 5834): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 5834): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 5834): wlan0: Scan completed in 0.524458 seconds
D/wpa_supplicant( 5834): nl80211: Received scan results (11 BSSes)
I/wpa_supplicant( 5834): [NULL] f0:f2:6d:22:99:3e freq=2442 level=-39
I/wpa_supplicant( 5834): [NULL] f4:f2:6d:22:99:3e freq=2442 level=-40
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c3 freq=2462 level=-55
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c0 freq=2462 level=-55
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:ef freq=5240 level=-68
I/wpa_supplicant( 5834): [NULL] 10:d3:8a:bb:6a:65 freq=2437 level=-66
,I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:e4 freq=2437 level=-83
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c5 freq=2462 level=-54
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-65
I/wpa_supplicant( 5834): [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-76
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-82
D/wpa_supplicant( 5834): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 1 BSSID f4:f2:6d:22:99:3e SSID 'NG700'
,D/wpa_supplicant( 5834): wlan0: BSS: Add new id 2 BSSID 00:1f:27:54:70:c3 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 3 BSSID 00:1f:27:54:70:c0 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 4 BSSID 00:1f:27:54:dd:ef SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 5 BSSID 10:d3:8a:bb:6a:65 SSID 'Komorka Samsung'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 6 BSSID 00:1f:27:54:dd:e4 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 7 BSSID 00:1f:27:54:70:c5 SSID 'RA-WINGS'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 8 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS'
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 9 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 10 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS'
D/wpa_supplicant( 5834): BSS: last_scan_res_used=11/32
D/wpa_supplicant( 5834): wlan0: Scan-only results received
D/wpa_supplicant( 5834): wlan0: Radio work 'scan'@0x5572e160f0 done in 0.526193 seconds
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 f0:f2:6d:22:99:3e]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 f4:f2:6d:22:99:3e]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 00:1f:27:54:70:c3]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 00:1f:27:54:70:c0]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 00:1f:27:54:dd:ef]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 10:d3:8a:bb:6a:65]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 00:1f:27:54:dd:e4]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:1f:27:54:70:c5]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:1e:4a:8f:e3:63]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 00:22:0d:46:1c:a3]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 00:1f:27:54:dd:e3]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=17 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
W/WifiMonitor(  970): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 5834): wlan0: Control interface command 'LIST_DONGLES'
I/WifiNative-HAL(  970): startHal
E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f75b7b400
I/WifiNative-HAL(  970): Could not start hal
E/WifiStateMachine(  970): [1,457,599,062,177 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 5834): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateM,achine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2406292c sup_state=SCANNING debouncing=false
,E/WifiAutoJoinController (  970): NG700_GUEST f0:f2:6d:22:99:3e rssi=-39 cap [WPA2-PSK-CCMP][ESS] is not scored
,E/WifiAutoJoinController (  970): NG700 f4:f2:6d:22:99:3e rssi=-40 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-40 freq=2442
E/WifiAutoJoinController (  970):  00:1f:27:54:70:c3 rssi=-55 cap [WPA-PSK-TKIP][WPA2-PSK-CCMP][ESS] is not scored
,E/WifiAutoJoinController (  970):  00:1f:27:54:70:c0 rssi=-55 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:dd:ef rssi=-68 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): Komorka Samsung 10:d3:8a:bb:6a:65 rssi=-66 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:dd:e4 rssi=-83 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1f:27:54:70:c5 rssi=-54 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1e:4a:8f:e3:63 rssi=-65 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:22:0d:46:1c:a3 rssi=-76 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1f:27:54:dd:e3 rssi=-82 cap [ESS] is not scored
,E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 11 now 1457599062187
E/WifiAutoJoinController (  970): newSupplicantResults size=11 known=1 true
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 5834): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  970): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  970): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-40,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController (  970): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
,E/WifiStateMachine(  970): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController (  970): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
,E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-40 freq=2442
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: null
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=3
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=true
,E/WifiStateMachine(  970): handleMessage: X,
E/WifiStateMachine(  970): handleMessage: E msg.what=131215
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-40 ;0 ,-127] any roam=0 rt=82692
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WifiManager( 1824): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiStateMachine(  970):  ConnectModeState !CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-40 ;0 ,-127] any roam=0 rt=82693
E/WifiStateMachine(  970): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  970): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
E/WifiConfigStore(  970): saving network history: "NG700"WPA_PSK gw: 04:8d:38:c3:6a:28 autojoin-status: 0 ephemeral=false choices:0 link:0 status:2 nid:0
E/WifiConfigStore(  970): writeKnownNetworkHistory write config "NG700"WPA_PSK
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
E/WifiConfigStore(  970): WifiConfigStore saveNetwork, size=1 SSID="NG700" Uid=1000/0
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=10): [REMOVED]
,W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!,
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='key_mgmt'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=7): [REMOVED]
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='proto'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=12): [REMOVED]
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='pairwise'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=14): [REMOVED]
,W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='group'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=27): [REMOVED]
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='priority'
,D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 5834): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  970): will read network variables netId=0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 5834): Do not allow key_data field to be exposed
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNA,ME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5834): CTRL_IFAC,E: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  970): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiConfigStore(  970): WifiConfigStore: saveNetwork got config back netId=0 uid=1000
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): CMD_AUTO_CONNECT did save config ->  nid=0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'ENABLE_NETWORK 0'
I/wpa_supplicant( 5834): ENABLE_NETWORK (0)
D/wpa_supplicant( 5834): CTRL_IFACE: ENABLE_NETWORK id=0
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='priority'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='::ORDERlimited'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/wpa_supplicant( 5834): CTRL_IFACE: Failed to set network variable '::ORDERlimited'
E/WifiConfigStore(  970): will read network variables netId=0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 5834): Do not allow key_data field to be exposed
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 5834): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5834): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  970): writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SELECT_NETWORK 0'
D/wpa_supplicant( 5834): CTRL_IFACE: SELECT_NETWORK id=0
D/wpa_supplicant( 5834): wlan0: Selecting BSS from priority group 691
D/wpa_supplicant( 5834): wlan0: 0: f0:f2:6d:22:99:3e ssid='NG700_GUEST' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-39
D/wpa_supplicant( 5834): 0: f0:f2:6d:22:99:3e ssid='NG700_GUEST' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 5834): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 5834): wlan0: 1: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-40 wps
D/wpa_supplicant( 5834): 1: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 5834): wlan0:    selected based on RSN IE
W/wpa_supplicant( 5834): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 5834):    selected WPA/WAPI AP f4:f2:6d:22:99:3e ssid='NG700'
D/wpa_supplicant( 5834): wlan0:    selected BSS f4:f2:6d:22:99:3e ssid='NG700'
D/wpa_supplicant( 5834): wlan0: Considering connect request: reassociate: 1  selected: f4:f2:6d:22:99:3e  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5572e11c00  current_ssid=0x5572e11c00
D/wpa_supplicant( 5834): wlan0: Request association with f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 07
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=28): 33 1a ef 11 1b ff ff ff 00 00 00 00 00 00 00 00 00 00 00 00 00 00 04 06 e6 e7 0d 00
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 07 0f 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 34 16 07 0f 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 88 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 5834): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 5834): wlan0: Add radio work 'connect'@0x5572e12680
D/wpa_supplicant( 5834): wlan0: First radio work item in the queue - schedule start immediately
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 5834): wlan0: Starting radio work 'connect'@0x5572e12680 after 0.000562 second wait
I/wpa_supplicant( 5834): check if in concurrent case
I/wpa_supplicant( 5834): wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz)
D/WifiMonitor(  970): Event [IFNAME=wlan0 Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz)]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=18 dispatchEvent: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz)
D/wpa_supplicant( 5834): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 5834): wlan0: Cancelling scan request
D/wpa_supplicant( 5834): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 5834): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 5834): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 5834): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 5834): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 5834): RSN: PMKSA cache search - network_ctx=0x5572e11c00 try_opportunistic=0
D/wpa_supplicant( 5834): RSN: Search for BSSID f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): RSN: No PMKSA cache entry found
D/wpa_supplicant( 5834): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 5834): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 5834): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 5834): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 5834): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 5834): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 5834): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 5834): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 5834): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5834): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 5834): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 5834): Limit connection to BSSID f4:f2:6d:22:99:3e freq=2442 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 5834): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 5834): nl80211: Unsubscribe mgmt frames handle 0x888888ddfa699989 (mode change)
D/wpa_supplicant( 5834): nl80211: Subscribe to mgmt frames with non-AP handle 0x5572e11100
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0104
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040a
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090a
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090b
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090c
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=090d
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0409506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=7f506f9a09
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0801
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=040e
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=06
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a07
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a11
D/wpa_supplicant( 5834): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5572e11100 match=0a1a
D/wpa_supplicant( 5834): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 5834):   * bssid=f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834):   * bssid_hint=f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834):   * freq=2442
D/wpa_supplicant( 5834):   * freq_hint=2442
D/wpa_supplicant( 5834):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 5834):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 5834):   * WPA Versions 0x2
D/wpa_supplicant( 5834):   * pairwise=0xfac04
D/wpa_supplicant( 5834):   * group=0xfac04
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 5834):   * akm=0xfac02
D/wpa_supplicant( 5834):   * Auth Type 0
D/wpa_supplicant( 5834): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5572e11c3a
D/wpa_supplicant( 5834): nl80211: Connect request send successfully
D/wpa_supplicant( 5834): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 5834): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 5834): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 5834): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 5834): wlan0: Control interface command 'RECONNECT'
E/WifiConfigStore(  970): setLastSelectedConfiguration -1
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5834): Ongoing scan action - reject new request
E/WifiStateMachine(  970): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131213
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TARGET_BSSID 18 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=82765
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TARGET_BSSID 18 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=82765
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TARGET_BSSID 18 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=82765
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TARGET_BSSID 18 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=82766
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=82766  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=82767  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATING
E/WifiStateMachine(  970): handleMessage: X
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 5834): EAPOL: disable timer tick
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 5834): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 5834): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5834): Wireless event: cmd=0x8c02 len=137
I/wpa_supplicant( 5834): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5834): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 5834): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 5834): nl80211: Connect event
D/wpa_supplicant( 5834): nl80211: Associated on 2442 MHz
D/wpa_supplicant( 5834): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): nl80211: Operating frequency for the associated BSS from scan results: 2442 MHz
D/wpa_supplicant( 5834): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 5834): wlan0: Association info event
D/wpa_supplicant( 5834): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): wlan0: freq=2442 MHz
D/wpa_supplicant( 5834): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 5834): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 5834): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5834): wlan0: Associated to a new BSS: BSSID=f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 5834): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
I/wpa_supplicant( 5834): wlan0: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
D/wpa_supplicant( 5834): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 5834): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 5834): TDLS: Remove peers on association
D/wpa_supplicant( 5834): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 5834): EAPOL: External notification - portValid=0
D/wpa_supplicant( 5834): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 5834): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 5834): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 5834): EAPOL: enable timer tick
D/wpa_supplicant( 5834): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 5834): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 5834): wlan0: Cancelling scan request
I/wpa_supplicant( 5834): htc_wext_set_keepalive +
I/wpa_supplicant( 5834): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 5834): getPrivFuncNum +	
I/wpa_supplicant( 5834): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 5834): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 5834): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 5834): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 5834): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 5834): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 5834):   replay_counter - hexdump(len=8): 00 00 00 ,00 00 00 00 01
D/wpa_supplicant( 5834):   key_nonce - hexdump(len=32): 89 53 63 e9 46 8e d0 72 73 53 0c 54 0e 92 1e 6f cc 7e 03 48 74 5d 63 ca d6 df 7f 09 ce 3f 8c aa
D/wpa_supplicant( 5834):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 5834): wlan0: WPA: RX message 1 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5834): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 5834): WPA: Renewed SNonce - hexdump(len=32): e6 fc de c1 fc 82 c9 5a bf cc b0 18 99 67 49 7e 66 c8 1c e2 37 d4 ab b0 bd 53 1f 33 9e 6c 8b c4
D/wpa_supplicant( 5834): WPA: Nonce1 - hexdump(len=32): e6 fc de c1 fc 82 c9 5a bf cc b0 18 99 67 49 7e 66 c8 1c e2 37 d4 ab b0 bd 53 1f 33 9e 6c 8b c4
D/wpa_supplicant( 5834): WPA: Nonce2 - hexdump(len=32): 89 53 63 e9 46 8e d0 72 73 53 0c 54 0e 92 1e 6f cc 7e 03 48 74 5d 63 ca d6 df 7f 09 ce 3f 8c aa
D/wpa_supplicant( 5834): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 5834): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 5834): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 5834): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 5834): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5834): WPA: Derived Key MIC - hexdump(len=16): 32 c3 23 74 fb f0 7f 06 81 ab a3 b3 cc 6b 97 4c
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  970): Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=21 dispatchEvent: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/WifiMonitor(  970): WifiMonitor: Got associated with event from string: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
D/WifiMonitor(  970): handleAssociatedWithEvent. Data= Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
D/HTCRequest(  970): WifiMonitor:getSSIDFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
D/HTCRequest(  970): WifiMonitor:getFrequencyFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=82880  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/HTCRequest(  970): WifiMonitor:getFreqFromEventString() 2442
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970),: WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 5834): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 5834): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 5834): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 5834): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 5834):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 5834):   key_nonce - hexdump(len=32): 89 53 63 e9 46 8e d0 72 73 53 0c 54 0e 92 1e 6f cc 7e 03 48 74 5d 63 ca d6 df 7f 09 ce 3f 8c aa
D/wpa_supplicant( 5834):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834):   key_rsc - hexdump(len=8): 90 f3 08 00 00 00 00 00
D/wpa_supplicant( 5834):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834):   key_mic - hexdump(len=16): 69 cf ee a5 c2 b6 2a ac 0f ae ce 51 2c c1 26 72
D/wpa_supplicant( 5834): RSN: encrypted key data - hexdump(len=56): 2f cb 25 68 bf 6b 89 dc 15 15 8a c1 c2 0d 7d c9 91 bd 14 02 b3 9c 5d de f0 f2 1f ac 82 a2 da 0a ...
D/wpa_supplicant( 5834): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 5834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 5834): wlan0: WPA: RX message 3 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 5834): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00 dd 16 00 0f ac 01 01 00 22 d8 ...
D/wpa_supplicant( 5834): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 5834): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 5834): wlan0: WPA: Sending EAPOL-Key 4/4
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 5834): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5834): WPA: Derived Key MIC - hexdump(len=16): 65 15 7a 17 ee 17 54 cf c7 cd e0 10 e8 62 c2 57
D/wpa_supplicant( 5834): wlan0: WPA: Installing PTK to the driver
D/PMS     (  970): acquireWL(39836d91): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5572e12390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 5834): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5834): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 5834):    addr=f4:f2:6d:22:99:3e
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 5834): EAPOL: External notification - portValid=1
D/wpa_supplicant( 5834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 5834): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 5834): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5834): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 5834): WPA: RSC - hexdump(len=6): 90 f3 08 00 00 00
D/wpa_supplicant( 5834): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5565839e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 5834): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 5834): nl80211: KEY_SEQ - hexdump(len=6): 90 f3 08 00 00 00
D/wpa_supplicant( 5834):    broadcast key
I/wpa_supplicant( 5834): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 5834): wlan0: Cancelling authentication timeout
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=82885  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/wpa_supplicant( 5834): wlan0: BLACKLIST REMOVE f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 5834): wlan0: Radio work 'connect'@0x5572e12680 done in 0.129101 seconds
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
I/wpa_supplicant( 5834): setConcurrentAPChannel: Set wifi.hotspot.channel to 7
E/WifiStateMachine(  970): handleMessage: X
D/HTCRequest(  970): WifiMonitor:getMacFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2442
D/WifiMonitor(  970): handleAssociatedWithEvent. Parsed MAC Address =f4:f2:6d:22:99:3e
D/WifiMonitor(  970): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  970): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2442
E/wpa_supplicant( 5834): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 5834): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 5834): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 5834): set send_ind_to_ndc = 0
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 5834): EAPOL: External notification - portValid=1
D/wpa_supplicant( 5834): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 5834): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 5834): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 5834): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5834): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 5834): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 5834): nl80211: Set supplicant port authorized for f4:f2:6d:22:99:3e
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
D/wpa_supplicant( 5834): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 5834): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 5834): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/wpa_supplicant( 5834): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=24 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiMonitor(  970): couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/PMS     (  970): releaseWL(39836d91): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST REMOVE f4:f2:6d:22:99:3e]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=25 dispatchEvent: BLACKLIST REMOVE f4:f2:6d:22:99:3e
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
E/WifiMonitor(  970): handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
W/ContextImpl( 5387): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WifiMonitor(  970): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=27 dispatchEvent: Connect to SSID: NG700
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
W/WifiMonitor(  970): couldn't identify event type - Connect to SSID: NG700
V/NetworkPolicy(  970): updateNotificationsLocked()
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine(  970): handleMessage: E msg.what=147500
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  970):  DisconnectedState !what:147500 0 0
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 4
E/WifiStateMachine(  970):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  970): Enter handleAssociatedWithEvent
D/WifiStateMachine(  970): Setting MAC Address to f4:f2:6d:22:99:3e
D/WifiStateMachine(  970): Associated
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiStateMachine(  970): mAssociatedMacAddress = f4:f2:6d:22:99:3e
D/WifiStateMachine(  970): Exit handleAssociatedWithEvent
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=82902  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 5
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=82910  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/TetherSettings( 5387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5387): Cust_ConnectToPC   : Internet_Sharing>true
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/        ( 5387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5387): Cust_ConnectToPC   : spcsc>false
D/        ( 5387): Cust_ConnectToPC   : IPT>true
D/        ( 5387): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5387): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=82911  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=82913  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147459
E/WifiStateMachine(  970): processMsg: DisconnectedState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=82914
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=82915
E/WifiStateMachine(  970): Network connection established
D/WifiStateMachine(  970): fetchFrequency(), freq = 2442
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/SmartNS_Utility( 5387): setISNotification
D/SmartNS_Utility( 5387): usb_cable_connect = 1
D/SmartNS_Utility( 5387): usb_denied = 0
I/SmartNS_PSService( 5387): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 6
E/WifiStateMachine(  970): transitionTo: destState=ObtainingIpState
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 7
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=4
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  970): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5387): usb_cable_connect = 1
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_Utility( 5387): usb_denied = 0
I/SmartNS_PSService( 5387): usb notificaiton:true
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 8
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1223): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5387): Tethered state change:false isNSOpening:false
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  970): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  970): L2ConnectedState f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid null
D/ConnectivityService(  970): Got NetworkAgent Messenger
E/WifiStateMachine(  970): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
D/wpa_supplicant( 5834): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  970): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  970): ObtainingIpAddress f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 5834): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 5834): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 5834): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5834): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5834): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/ConnectivityService(  970): NetworkAgent connected
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WISPrService( 5387): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): Start Dhcp Watchdog 1
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: ObtainingIpState
I/RemoteViews( 1223): reapply : com.android.settings 2 36
E/WifiStateMachine(  970):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=82976  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=82977  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
D/WISPrService( 5387): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2442, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=82977  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ObtainingIpState
,E/WifiStateMachine(  970):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=2442 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1605149149] from screen [on:0 period:1605149149]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=2442 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1605149150]
E/WifiStateMachine(  970):  get link layer stats 2
I/WifiNative-HAL(  970): startHal
E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f75b7b400
I/WifiNative-HAL(  970): Could not start hal
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
I/wpa_supplicant( 5834): environment dirty rate=0 [3][0][0]
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -40 abnormalRssiCnt = 0 newLinkSpeed = 150
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-40 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-40 "NG700"WPA_PSK
,D/WifiWatchdogStateMachine(  970): RSSI current: 0 new: -40, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED -1 -> 3
,E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=0.50 txretriesrate=0.00 rxrate=0.00 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): calculateWifiScore() report new score 60
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -40, 3
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
D/ConnectivityService(  970): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
,E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=196612
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  970): acquireWL(96e6983): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
D/WifiStateMachine(  970): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  970): setDhcpActive: true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  970): do suspend false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 5834): Power_Mode_Type mode = 1
,I/wpa_supplicant( 5834): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
D/wpa_supplicant( 5834): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 5834): nl80211: Rekey offload event for BSSID f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 5834): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): Unexpected BatchedScanResults :null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@67b0700 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@67b0700 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): noteBatchedScanstop()
E/WifiStateMachine(  970): handleMessage: X,
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/dhcpcd  ( 5933): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5933): version 5.5.6 starting,
E/dhcpcd  ( 5933): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 5933): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 5933): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 5933): wlan0: broadcasting for a lease
,I/dhcpcd  ( 5933): wlan0: sending DISCOVER (xid 0xca8ed662), next in 0.54 seconds
,D/wpa_supplicant( 5834): EAPOL: startWhen --> 0,
D/wpa_supplicant( 5834): EAPOL: disable timer tick
,I/dhcpcd  ( 5933): wlan0: sending DISCOVER (xid 0xca8ed662), next in 1.53 seconds,
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  970): handleMessage: E msg.what=131212
,E/WifiStateMachine(  970): processMsg: ObtainingIpState,
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  970): handleMessage: X
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 3162): handler message = 4011,
E/HtcModeClient( 3162): Check connection and retry 9 times.
,I/dhcpcd  ( 5933): wlan0: offered 192.168.1.102 from 192.168.1.1,
I/dhcpcd  ( 5933): wlan0: sending REQUEST (xid 0xca8ed662), next in 0.58 seconds
,I/dhcpcd  ( 5933): wlan0: ignoring offer of 192.168.1.102 from 192.168.1.1,
,D/PMS     (  970): acquireWL(28842b39): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{2c87f57e: PendingIntentRecord{241adf android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85372, Int=0
D/PMS     (  970): releaseWL(28842b39): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,I/dhcpcd  ( 5933): wlan0: acknowledged 192.168.1.102 from 192.168.1.1
,I/dhcpcd  ( 5933): wlan0: leased 192.168.1.102 for 172800 seconds
I/dhcpcd  ( 5933): autoip env[11]:autoip=DISABLE
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  970): handleMessage: X
,I/jxcore-log( 5686): My device name is: HTC-HTC One M8s,
I/jxcore-log( 5686): 
,I/dhcpcd  ( 5933): bind_interface: daemonise
,D/PMS     (  970): acquireWL(3709932c): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
,V/AlarmManager(  970): sending alarm PendingIntent{19f341f5: PendingIntentRecord{2329eb8a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=85805, Int=0
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  970): releaseWL(3709932c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  970): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=196613
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 5834): Power_Mode_Type mode = 0
I/wpa_supplicant( 5834): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 5834): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
,E/WifiStateMachine(  970): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  970): releaseWL(96e6983): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  970): WifiStateMachine DHCP successful
E/WifiStateMachine(  970): wifistatemachine handleIPv4Success <IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds>
E/WifiStateMachine(  970): link address 192.168.1.102/24
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  970): gateway: /192.168.1.1
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 5834): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 5834): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131210
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [5][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -45 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-45 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-42 "NG700"WPA_PSK
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/wpa_supplicant( 5834): wlan0: Control interface command 'BLACKLIST clear'
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/wpa_supplicant( 5834): wlan0: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -45, 3,
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=29 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  970): NetworkAgent != null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -45, Link speed: 150, Frequency: 2442, Net ID: 0, Metered hint: false
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -45, Link speed: 150, Frequency: 2442, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
E/WifiStateMachine(  970): transitionTo: destState=ConnectedState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
D/HtcWifiWanDetect(  970): WAN detection
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  970): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  970): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  970): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/HtcWifiWanDetect(  970): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  970): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 9
D/ConnectivityService(  970): Adding iface wlan0 to network 100
E/WifiStateMachine(  970): handleMessage: X
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  970):  packet count Tx=3 Rx=4
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 0
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 10
E/WifiTrafficPoller(  970):  packet count Tx=3 Rx=4
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5387): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/ConnectivityService(  970): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/ConnectivityService(  970): Adding Route [fe80::/64 -> :: wlan0] to network 100
E/WifiStateMachine(  970):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): handleMessage: X
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  970): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100,
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 100]
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WISPrService( 5387): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): currentScore = 0, newScore = 20
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Connected
D/ConnectivityService(  970): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  970): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WIFI    (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sendGeneralBroadcastDelayed, restrictEnable=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=-3ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/PMS     (  970): acquireWL(1912b618): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethe,ring(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  970): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 100]
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  970): updateNotificationsLocked()
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capa,bilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/DATA_ICON( 1223): dataConnected: false/false
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SecurityController( 1223): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/PMS     (  970): releaseWL(1912b618): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1223): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
D/DATA_ICON( 1223): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
I/SecurityController( 1223): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2442 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1605152156] gl hn u24 rssi=-35 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2442 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1605152157] gl hn u24 rssi=-35 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 1
I/WifiNative-HAL(  970): startHal
E/wifi    (  970): getStaticLongField sWifiHalHandle 0x7f75b7b400
,I/WifiNative-HAL(  970): Could not start hal
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -45 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-45 linkspeed=150
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  970): BroadcastRSSIForIMS, newrssi =-45 , oldRssi= -200
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-43 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -45, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.25 txretriesrate=0.00 rxrate=2.00 userTriggerdPenalty0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -45, 3
E/WifiStateMachine(  970): handleMessage: X
,D/PMS     (  970): acquireWL(9433656): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072},
V/AlarmManager(  970): sending alarm PendingIntent{8b086d7: PendingIntentRecord{1d891bc4 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457599065780, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{176ebaad: PendingIntentRecord{5d461e2 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1457599065583, Int=20000
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
D/PMS     (  970): releaseWL(9433656): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-45 f=2442 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=2.0 fiv=40000 [on:0 tx:0 rx:0 period:265] from screen [on:0 period:1605152444]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-45 f=2442 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=2.0 fiv=40000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1605152444]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.25 rxSuccessRate=2.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=1457599065789 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN try full band scan age=1457599065789 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN bump interval =60000
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5834): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 5834): wpa_supplicant_scan enter
D/wpa_supplicant( 5834): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 5834): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 5834): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 5834): WPS:  * Request Type
D/wpa_supplicant( 5834): WPS:  * Config Methods (4288)
D/wpa_supplicant( 5834): WPS:  * UUID-E
D/wpa_supplicant( 5834): WPS:  * Primary Device Type
D/wpa_supplicant( 5834): WPS:  * RF Bands (3)
D/wpa_supplicant( 5834): WPS:  * Association State
,D/wpa_supplicant( 5834): WPS:  * Configuration Error (0)
D/wpa_supplicant( 5834): WPS:  * Device Password ID (0)
D/wpa_supplicant( 5834): WPS:  * Manufacturer
D/wpa_supplicant( 5834): WPS:  * Model Name
D/wpa_supplicant( 5834): WPS:  * Model Number
D/wpa_supplicant( 5834): WPS:  * Device Name
D/wpa_supplicant( 5834): WPS:  * Version2 (0x20)
D/wpa_supplicant( 5834): P2P: * P2P IE header
D/wpa_supplicant( 5834): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 5834): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 5834): wlan0: Add radio work 'scan'@0x5572e12680
D/wpa_supplicant( 5834): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 5834): wlan0: Starting radio work 'scan'@0x5572e12680 after 0.000042 second wait
D/wpa_supplicant( 5834): wlan0: nl80211: scan request
D/wpa_supplicant( 5834): nl80211: Add NL80211_SCAN_FLAG_FLUSH
D/wpa_supplicant( 5834): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 5834): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 5834): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 5834): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 5834): wlan0: Own scan request started a scan in 0.000110 seconds
I/wpa_supplicant( 5834): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): [1,457,599,065,792 ms] noteScanstart no scan source
E/WifiStateMachine(  970): handleMessage: X
,I/art     (  970): Explicit concurrent mark sweep GC freed 60928(3MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.976ms total 147.617ms
,D/PMS     (  970): releaseWL(2cbbbdd3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/Finsky  ( 5411): [557] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5411): [1] 5.onFinished: Installation state replication succeeded.,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=3 Rx=4,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=3 Rx=5
E/WifiTrafficPoller(  970): notifying of data activity 1
,D/WIFI_ICON( 1223): WifiActivity: 1
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1223): WifiActivity: 2
E/WifiTrafficPoller(  970):  packet count Tx=6 Rx=5
E/WifiTrafficPoller(  970): notifying of data activity 2
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  970): acquireWL(80cb973): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: true
D/PMS     (  970): acquireWL(2fde3030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,I/ConnectivityHelper( 1537): [onReceive] WIFI(1): CONNECTED
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5971 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5990 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/PMS     (  970): acquireWL(96954a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(3d5aba2e): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 970 1000 WorkSource{10024}
,D/PMS     (  970): acquireWL(193e3eb): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 970 1000 WorkSource{10024}
,D/PMS     (  970): releaseWL(193e3eb): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2442 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:2733] from screen [on:0 period:1605155182] gl hn u24 rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2442 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605155184] gl hn u24 rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [3][0][0],
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-44 "NG700"WPA_PSK
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.62 txretriesrate=0.00 rxrate=1.50 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
E/WifiStateMachine(  970): handleMessage: X
,I/MusicStore( 5971): Database version: 120
,D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
,D/libc    ( 4539): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4539): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4539): [NET] android_getaddrinfo_proxy+
D/libc    ( 4539): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6021 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/PMS     (  970): acquireWL(1963ba19): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 970 1000 WorkSource{10024},
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  970): releaseWL(2fde3030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/GpsLocationProvider(  970): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/VoldConnector(  970): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
,W/ContextImpl( 5971): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/PMS     (  970): acquireWL(4bc97b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,E/GpsLocationProvider(  970): No APN found to select.
,D/PMS     (  970): acquireWL(38727942): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PMS     (  970): releaseWL(38727942): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  970): acquireWL(17858690): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PhoneStatusBar( 1223): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/GpsLocationProvider(  970): [handleMessage] INJECT_NTP_TIME
D/PMS     (  970): releaseWL(17858690): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/MdScPhnSt( 6021): [68b.1.]  listen tmrbb8
,W/ContextImpl( 5971): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  970): SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5971): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5971): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
D/MdScDataSum( 6021): [68b.1.] summary 118:p1 ignore
W/ResourcesManager( 5971): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  970): acquireWL(6e42745): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,V/JNIHelp ( 5971): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
D/PMS     (  970): releaseWL(96954a9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 17652(990KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 10.237ms total 66.080ms
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success,
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
W/ActivityThread( 5971): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
W/System  ( 5971): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2415362b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5971): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5971): GMSCore installation verified
I/ConfigStore( 5971): Config Database version: 1
I/ActivityManager(  970): Killing 5364:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5364
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/GoogleURLConnFactory( 1913): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  970): Recipient 5364
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  970): Find DNS Address www.htc.com/104.81.130.175
D/libc    ( 4539): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4539): [NET] android_getaddrinfofornet-, SUCCESS
D/AlarmManager(  970):  invoke hookTimeZoneToRadio(true, 3600)
D/GpsLocationProvider(  970): NTP server returned: 1457599071502 (Thu Mar 10 09:37:51 CET 2016) reference: 89585 certainty: 122 system time offset: 2411
V/AlarmManager(  970): hookRadio - sign: true offset:3600
,D/PMS     (  970): acquireWL(204cf9fd): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(3d5aba2e): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  970): releaseWL(204cf9fd): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  970): [handleMessage] INJECT_NTP_TIME_FINISHED
,D/PMS     (  970): releaseWL(80cb973): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/GpsLocationProvider(  970): handleReportAgpsStatus with type = 29300status = 28769ipaddr = [B@b9fb6f2
,D/GpsLocationProvider(  970): Received Unknown AGPS status: 28769,
D/GpsLocationProvider(  970): xtraDownloadRequest
D/PMS     (  970): acquireWL(3d7438f9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  970): acquireWL(325f3e9f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/PMS     (  970): releaseWL(3d7438f9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AlarmManager(  970): setTime() is invoked. time=1457599071506
W/AlarmManagerService(  970): Unable to set rtc to 1457599071: Invalid argument
E/QC-time-services(  474): Daemon:tod_update_ind_cb: Got Update from modem msg_id 39
,I/IntentController( 1223): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1303): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
W/DriveInitializer( 4218): Background init thread started
,E/QC-time-services(  474): Daemon:tod_update_ind_cb: Got Update from modem msg_id 39
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
I/FeedActionBar( 1537): updateLastUpdatedTime(in String) LAST UPDATED 9:36
,I/ActivityManager(  970): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=6065 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/PMS     (  970): acquireWL(3caf0e31): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,I/ConfigFetchService( 4218): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  970): releaseWL(3caf0e31): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConfigService( 1913): onCreate
,I/ConfigFetchService( 4218): running network task: configservice_periodic
,E/WakeLock( 4218): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,D/PMS     (  970): acquireWL(19355c6d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
I/ConfigFetchService( 4218): launchTask
,I/ConfigFetchService( 4218): service connected
I/Clock   ( 1223): updateClock:09:37 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:37 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:37 Europe/Warsaw
D/DotMatrix( 1303): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/ConfigFetchService( 4218): ConfigApi connection successful.
W/ResourcesManager( 6065): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5971, uid=10159, userID:0
,W/DriveInitializer( 4218): Awaiting to be initialized,
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,D/CalendarApplication( 6065): onCreate
,D/MediaRouterService(  970): Client com.google.android.music (pid 5971): Registered
,D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4539): [NET] android_getaddrinfofornet-, err=8
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/AlertReceiver( 6065): beginStartingService
,D/PMS     (  970): acquireWL(24dd1f87): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 6065 10010 null
,I/MediaRouter( 5971): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6098 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  970): Killing 5581:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5581
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/VoldConnector(  970): SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
,W/ContextImpl( 4218): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,I/ActivityManager(  970): Recipient 5581
,I/HtcModeClient( 3162): handler message = 4011
,E/HtcModeClient( 3162): Check connection and retry 10 times.
,V/MusicLeanback( 5971): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=14 Rx=11
E/WifiTrafficPoller(  970): notifying of data activity 3
D/WIFI_ICON( 1223): WifiActivity: 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
I/NetworkMonitor( 5971): type=WIFI subType= reason=null isConnected=true
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/ResourcesManager( 6098): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/NetworkMonitor( 5971): type=WIFI subType= reason=null isConnected=true
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
W/DriveInitializer( 4218): Background init thread ended
,I/CalendarProvider2( 6098): Created com.android.providers.calendar.CalendarAlarmManager@2bf88067(com.htc.providers.calendar.HtcCalendarProvider@26983e14)
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5971, uid=10159, userID:0
,D/CalendarProvider2( 6098): wait start:true
,I/GHttpClientFactory( 5971): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5971): Using platform SSLCertificateSocketFactory
,I/art     ( 3591): Explicit concurrent mark sweep GC freed 3822(157KB) AllocSpace objects, 0(0B) LOS objects, 57% free, 1506KB/3MB, paused 379us total 35.054ms
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(2644225f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(1963ba19): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  970): acquireWL(e32857b): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 970 1000 WorkSource{10024}
,D/PMS     (  970): releaseWL(2644225f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
D/PMS     (  970): acquireWL(99fd44): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PMS     (  970): releaseWL(99fd44): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/CalendarProvider2( 6098): wait end:false,
,D/HtcAlertService( 6065): start to updateAlertNotification!,
,D/HtcAlertService( 6065): No fired or scheduled alerts
,D/HtcAlertUtils( 6065): -- cancelReminderNotification --
,D/HtcAlertUtils( 6065): broadcastExistReminder!
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): releaseWL(24dd1f87): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/AutoSetting( 1449): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  970): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.OneTimeOnConnectedReceiver: pid=6144 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/PMS     (  970): acquireWL(141628f3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,W/AlertReceiver( 6065): stopSelfResult true,
,D/AutoSetting( 1449): service - onCreate()
,D/PMS     (  970): releaseWL(e32857b): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
,I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=6169 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,D/AutoSetting( 1449): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/LocationManagerService(  970): request 155f7dab passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/PMS     (  970): releaseWL(141628f3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/LocationManagerService(  970): provider request: passive ProviderRequest[ON interval=0]
I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/WeatherUtility( 5837): Weather sync is On
,D/AutoSetting( 1449): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1449): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1449): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1449): service - handleMessage() setting current location null
,W/ResourcesManager( 6169): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/WeatherRequest( 5837): request cur loc, but there is no sys cur
,W/Settings( 5837): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5837): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/PMS     (  970): acquireWL(d6b85e5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 6169 10069 null
,D/PMS     (  970): acquireWL(2db1f8ba): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 6169 10069 null,
,D/PMS     (  970): releaseWL(d6b85e5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null,
I/RemoteViews( 1537): reapply : com.htc.widget.weatherclock 12 17
,I/ActivityManager(  970): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=6194 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a,
,D/TodoTaskshortcut( 6169): update TASK shortcut>
,I/TodoTaskNotifyService( 6169): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 5686): 
,E/cutils-trace( 6215): Error opening trace file: Permission denied (13),
I/dex2oat ( 6215): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6215): dex2oat: override thread count:4
,I/art     (  970): Explicit concurrent mark sweep GC freed 23977(1188KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/24MB, paused 1.746ms total 165.943ms,
D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data
,I/TodoTaskNotifyService( 6169): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  970): releaseWL(2db1f8ba): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/WorldClock.Global( 6194): isHEPDevice = true
,W/NotifyReceiver( 6169): stopSelfResult true
I/ActivityManager(  970): Killing 5605:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5605
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/WorldClock.AlarmUtils( 6194): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  970): Recipient 5605
,I/WorldClock.AlarmUtils( 6194): Cancel any alarm from alarm manager,
I/WorldClock.AlarmUtils( 6194): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon,
,I/IntentController( 1223): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/WorldClock.Global( 6194): isHEPDevice = true
,I/ActivityManager(  970): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/WorldClock.AlarmUtils( 6194): isDeviceEncryptionEnabled = false,
,I/WorldClock.AlarmUtils( 6194): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  970): Killing 4571:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=4571
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/WorldClock.DmdCmd( 6194): This version is general off mode alarm function,
,W/WorldClock.DmdCmd( 6194): Conn: fail e = java.io.IOException: No such file or directory
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
I/art     (  430): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 277us total 29.505ms
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
D/PMS     (  970): acquireWL(246e405e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  970): releaseWL(325f3e9f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  970): releaseWL(246e405e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 225us total 25.428ms
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 136us total 18.685ms,
,I/ActivityManager(  970): Recipient 4571
,D/TimeService( 6224): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457599072731,
,E/QC-time-services(  474): Daemon:Update to modem bit set
E/QC-time-services( 6224): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  474): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=77 rxSum=75} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=89 Rx=87
,D/Process (  970): killProcessQuiet, pid=5644,
I/ActivityManager(  970): Killing 5644:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/CalendarProvider2( 6098): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6098): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  970): Recipient 5644
,I/dex2oat ( 6215): dex2oat took 796.032ms (threads: 4),
,D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4,
D/libc    ( 4539): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4539): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4539): [NET] android_getaddrinfo_proxy+
D/libc    ( 4539): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/Process (  970): killProcessQuiet, pid=5480
I/ActivityManager(  970): Killing 5480:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  970): acquireWL(e22b255): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Recipient 5480
,D/PMS     (  970): acquireWL(3285d5b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(e22b255): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  970): killProcessQuiet, pid=5452
I/ActivityManager(  970): Killing 5452:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PhenotypeFlagCommitter( 1913): Experiment Configs successfully retrieved for com.google.android.gms.phenotype,
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 5686): 
,I/ActivityManager(  970): Recipient 5452
,I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6144): ApplicationMonitor {1e7c49fe}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4539): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4539): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4539): [NET] android_getaddrinfofornet-, SUCCESS
,D/PMS     (  970): releaseWL(3285d5b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(6e42745): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(27c56da4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  970): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6254 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=2, flag=1, pid=6144, uid=10071, userID:0
,D/PMS     (  970): releaseWL(27c56da4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(74fd70d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/PushClient( 6144): OnConnectedHandler {254f080a}: handle(): Try update on network connected.
I/PushClient( 6144): PnsModel {37fb01b9}: update(): Update registration caused by: android.net.conn.CONNECTIVITY_CHANGE
,I/PushClient( 6144): PnsConfigModel {143170b0}: <init>(): Use dm-client for provisioning.
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5686): 
,W/System.err( 6144): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6144): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6144): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6144): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,D/PhoneMonitor( 6254): Register our PhoneStateListener,
D/PMS     (  970): acquireWL(2e597d0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10176 com.google.android.youtube}
I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6276 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6295 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  970): releaseWL(74fd70d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(39e5d927): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4218 10024 null
,D/PMS     (  970): acquireWL(a3187d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/MobileConnectivityChangeReceiver( 6254): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6254): onReceive CONNECTIVITY_CHANGE networkType=1
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 5686): 
,D/PMS     (  970): acquireWL(10719d7d): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4218 10024 WorkSource{10024 com.google.android.gms},
,D/Process (  970): killProcessQuiet, pid=5337,
I/ActivityManager(  970): Killing 5337:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5686): 
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PMS     (  970): releaseWL(a3187d4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5686): 
,D/PhoneMonitor( 6254): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6254): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,I/ActivityManager(  970): Recipient 5337
,D/PMS     (  970): releaseWL(39e5d927): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  970): releaseWL(10719d7d): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(e4ce0c3): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(31ff9479): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
I/DeviceManagement( 6276): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6276 dbg=false s=true
,D/PMS     (  970): releaseWL(e4ce0c3): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/DeviceManagement( 6276): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 6276): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6276): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,D/PMS     (  970): acquireWL(3b92c61f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,I/DeviceManagement( 6276): WorkflowService: Starting workflow service
,I/DeviceManagement( 6276): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
I/DeviceManagement( 6276): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@e02bc03] args=[Bundle[mParcelledData.dataSize=720]]
D/PMS     (  970): releaseWL(3b92c61f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4218): Checking schedule, now: 1457599073614 next: 1456765623471
I/CheckinService( 4218): active receiver: enabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4218, uid=10024, userID:0
,I/CheckinService( 4218): Preparing to send checkin request
I/EventLogService( 4218): Accumulating logs since 1457598487815,
,I/DeviceManagement( 6276): NetworkChangeWorkflow: ==================================================,
I/DeviceManagement( 6276): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 6276): NetworkChangeWorkflow: ==================================================,
,I/DeviceManagement( 6276): ModelRegistry: Loading model meta data from resources...
,D/PMS     (  970): acquireWL(15db8458): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4218, uid=10024, userID:0
I/DeviceManagement( 6276): SessionStateController: Checking invariants...
,I/iu.SyncManager( 4218): SYNC; picasa accounts,
,D/NetworkLogImpl( 4218): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4218): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4218): num queued entries: 0
I/iu.UploadsManager( 4218): num updated entries: 0
I/iu.SyncManager( 4218): NEXT; no task
,D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4218): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=101 Rx=98
,I/ActivityManager(  970): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6335 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CheckinRequestBuilder( 4218): Checkin reason type: 8 attempt count: 1,
,W/ResourcesManager( 6295): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  431): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 503us total 35.196ms
E/WifiTrafficPoller(  970): ADD_CLIENT: 8
D/WifiService(  970): New client listening to asynchronous messages
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4218): Failed to find provider info for com.google.android.wearable.settings
,I/DeviceManagement( 6276): BackgroundController: Invariants are unchanged.,
,W/ResourcesManager( 6335): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 577us total 27.034ms
,I/DeviceManagement( 6276): SessionStateController: Checking invariants...
,I/GcmGroups( 4218): Failed to subscribe to group.,
I/GcmGroups( 4218): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 4218): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 4218): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 4218): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 4218): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 4218): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 4218): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 4218): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 4218): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 4218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 4218): 	at android.os.Looper.loop(Looper.java:155)
I/GcmGroups( 4218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GcmGroups( 4218): Groups upload failed, retrying in 24000:00:00,
I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 368us total 21.686ms
,V/JNIHelp ( 6295): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6295): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6295): Installed default security provider GmsCore_OpenSSL
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:5368] from screen [on:0 period:1605160565] gl hn u24 rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=2.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605160567] gl hn u24 rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=8 [97][8][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-45 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=48.81 txretriesrate=0.00 rxrate=47.25 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3,
,I/DeviceManagement( 6276): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 19881(1017KB) AllocSpace objects, 4(100KB) LOS objects, 47% free, 4MB/8MB, paused 2.591ms total 82.693ms,
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,I/Babel_SMS( 6335): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6335): MmsConfig.loadMmsSettings
,I/ActivityManager(  970): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6375 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 6295): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6335, uid=10112, userID:0
,I/DeviceManagement( 6276): Perf: *** Cache update - start...
,I/DeviceManagement( 6276): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 6276): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 6276): Perf: *** Enabled app cache update - complete: 1 ms
,I/DeviceManagement( 6276): Perf: *** Config cache update - start...
,I/DeviceManagement( 6276): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 6276): ConfigCacheController: *** Updating stale config cache entries...
,W/HtcWrapAdjustableCursorFactory( 6375): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/wpa_supplicant( 5834): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 5834): wlan0: nl80211: New scan results available
D/wpa_supplicant( 5834): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 5834): wlan0: Event SCAN_RESULTS (3) received,
I/wpa_supplicant( 5834): Got an original EVENT_SCAN_RESULTS
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 5834): wlan0: Scan completed in 6.016351 seconds
D/wpa_supplicant( 5834): nl80211: Associated on 2442 MHz
D/wpa_supplicant( 5834): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 5834): nl80211: Received scan results (19 BSSes)
D/wpa_supplicant( 5834): nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
I/wpa_supplicant( 5834): [NULL] f0:f2:6d:22:99:3e freq=2442 level=-39
I/wpa_supplicant( 5834): [NULL] f4:f2:6d:22:99:3e freq=2442 level=-46
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-55
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-56
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c4 freq=2462 level=-54
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c3 freq=2462 level=-55
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c0 freq=2462 level=-55
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:ef freq=5240 level=-68
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-65
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-66
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-66
I/wpa_supplicant( 5834): [NULL] 10:d3:8a:bb:6a:65 freq=2437 level=-68
I/wpa_supplicant( 5834): [NULL] 00:16:a6:1f:06:5c freq=2462 level=-78
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:e4 freq=2437 level=-83
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c2 freq=2462 level=-54
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:70:c5 freq=2462 level=-54
I/wpa_supplicant( 5834): [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-64
I/wpa_supplicant( 5834): [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-79
I/wpa_supplicant( 5834): [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-80
D/wpa_supplicant( 5834): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 11 BSSID 00:1e:4a:8f:e3:6b SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 12 BSSID 00:1e:4a:8f:e3:6f SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 13 BSSID 00:1f:27:54:70:c4 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 14 BSSID 00:1e:4a:8f:e3:62 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 15 BSSID 00:1e:4a:8f:e3:64 SSID '\x00'
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 16 BSSID 00:1e:4a:8f:e3:60 SSID '\x00'
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 00:1e:4a:8f:e3:6b]
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 17 BSSID 00:16:a6:1f:06:5c SSID ''
D/wpa_supplicant( 5834): wlan0: BSS: Add new id 18 BSSID 00:1f:27:54:70:c2 SSID '\x00'
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 00:1e:4a:8f:e3:6f]
D/wpa_supplicant( 5834): BSS: last_scan_res_used=19/32
D/wpa_supplicant( 5834): wlan0: Scan-only results received
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:1f:27:54:70:c4]
D/wpa_supplicant( 5834): wlan0: Radio work 'scan'@0x5572e12680 done in 6.017970 seconds
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 00:1e:4a:8f:e3:62]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 00:1e:4a:8f:e3:64]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 00:1e:4a:8f:e3:60]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 00:16:a6:1f:06:5c]
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 00:1f:27:54:70:c2]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine,(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=11 known=1 got=11 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 5834): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,457,599,074,178 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 5834): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ee22939 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG700_GUEST f0:f2:6d:22:99:3e rssi=-39 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 f4:f2:6d:22:99:3e rssi=-46 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-46 freq=2442
E/WifiAutoJoinController (  970):  00:1f:27:54:70:c3 rssi=-55 cap [WPA-PSK-TKIP][WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:70:c0 rssi=-55 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:dd:ef rssi=-68 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): Komorka Samsung 10:d3:8a:bb:6a:65 rssi=-68 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:dd:e4 rssi=-83 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1f:27:54:70:c5 rssi=-54 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1e:4a:8f:e3:63 rssi=-64 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:22:0d:46:1c:a3 rssi=-79 cap [ESS] is not scored
E/WifiAutoJoinController (  970): RA-WINGS 00:1f:27:54:dd:e3 rssi=-80 cap [ESS] is not scored
E/WifiAutoJoinController (  970):  00:1e:4a:8f:e3:6b rssi=-55 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1e:4a:8f:e3:6f rssi=-56 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:70:c4 rssi=-54 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1e:4a:8f:e3:62 rssi=-65 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1e:4a:8f:e3:64 rssi=-66 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1e:4a:8f:e3:60 rssi=-66 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:16:a6:1f:06:5c rssi=-78 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  970):  00:1f:27:54:70:c2 rssi=-54 cap [WEP][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 19 now 1457599074191
E/WifiAutoJoinController (  970): newSupplicantResults size=19 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 5834): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
E/WifiAutoJoinController (  970): ssid=NG700
E/WifiAutoJoinController (  970): id=0
E/WifiAutoJoinController (  970): mode=station
E/WifiAutoJoinController (  970): pairwise_cipher=CCMP
E/WifiAutoJoinController (  970): group_cipher=CCMP
E/WifiAutoJoinController (  970): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  970): wpa_state=COMPLETED
E/WifiAutoJoinController (  970): ip_address=192.168.1.102
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/cutils-trace( 6398): Error opening trace file: Permission denied (13)
E/WifiAutoJoinController (  970): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
I/dex2oat ( 6398): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2001819053.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads2001819053.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6398): dex2oat: override thread count:4
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-46,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-46 freq=2442 Current: f4:f2:6d:22:99:3e
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
D/MessageFrequencyProvider( 6375): onCreate
D/WifiManager( 1824): getScanResults: Base Package Name=com.google.android.gms, uid=10024
V/GetPrviateResource( 6375): GetPrviateResource
V/GetPrviateResource( 6375): GetPrviateResource
I/art     ( 6276): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
I/art     ( 6276): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,D/MmsCustomizationProvider( 6375): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MessageCustFlag( 6375): sense_version=6.0
D/BTAccessoryUtil( 6375): createReceiver
D/BTAccessoryUtil( 6375): registerReceiver return intent = null
D/MessageCustFlag( 6375): sku_id=118
D/MmsCustomizationProvider( 6375): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/HtcBuildUtils( 6375): getRATByHtcTelephonyCapability:1
W/SystemReader( 6375): Cannot find qct_8960_interface, use default value instead
I/Babel_SMS( 6335): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6335): MmsConfig.loadFromDatabase
W/Settings( 6335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/YouTube MDX( 6295): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/Babel_SMS( 6335): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6335): MmsConfig.loadFromResources
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,D/libc    ( 6295): [NET] android_getaddrinfofornet-, SUCCESS
,I/Babel_Crash( 6335): startup - clean
,E/Babel_SMS( 6335): canonicalizeMccMnc: invalid mccmnc nullnull
W/System.err( 6276): Starting the internal HTTP client
I/Babel_SMS( 6335): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 63
D/AccFlag ( 1489): sku_id=118
D/ContactMessageStore( 1489): notify MmsSms
D/AccFlag ( 1489): sense_version=6.0
D/AccFlag ( 1489): sku_id=118
I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/Babel   ( 6335): deleted: false for 0
,I/dex2oat ( 6398): dex2oat took 113.296ms (threads: 4)
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1489): sku_id=118
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 63
D/AccFlag ( 1489): sku_id=118
I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/VoldConnector(  970): SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 6295): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1489): sku_id=118
,D/BuildInfo( 6276): Created new instance: com.htc.cs.lib.hms.BuildInfo@e3997f4,
I/DeviceManagement( 6276): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  970): acquireWL(bbcb401): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(bbcb401): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 6276): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6276): [NET] android_getaddrinfo_proxy+
D/PMS     (  970): acquireWL(132c84e7): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 6276): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6276): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 6276): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6276): [NET] android_getaddrinfo_proxy+
D/libc    ( 6276): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.android.phone ] tid: 56
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6276): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(120b29df): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1913): Connected
,D/PMS     (  970): releaseWL(15db8458): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(120b29df): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/ActionCombine( 1913): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/art     (  970): Explicit concurrent mark sweep GC freed 19841(1061KB) AllocSpace objects, 2(56KB) LOS objects, 33% free, 16MB/24MB, paused 1.752ms total 169.324ms
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6335, uid=10112, userID:0
D/PMS     (  970): acquireWL(202284fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/GCM     ( 1913): Ack for not saved message 2
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6335, uid=10112, userID:0
D/GCM     ( 1913): Message class com.google.f.a.a.p
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6335, uid=10112, userID:0
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6335, uid=10112, userID:0
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6335, uid=10112, userID:0
D/PMS     (  970): releaseWL(202284fb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/ResourcesManager( 1303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 4218): awaiting user notification for token
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6430 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/VideoCapabilities( 6335): Unrecognized profile 2130706433 for video/avc
I/RemoteViews( 1223): apply : com.google.android.gms 0 17 6 40
,W/VideoCapabilities( 6335): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6335): could not parse size range '64x64-1920X1080'
,D/VoldConnector(  970): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 6295): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  970): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
W/AudioCapabilities( 6335): Unsupported mime audio/qcelp
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 6295): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  970): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 6295): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
W/AudioCapabilities( 6335): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6335): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6335): Unsupported mime video/x-ms-wmv
W/InstanceID/Rpc( 6295): Found 10024
,I/ActivityManager(  970): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6456 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/VoldConnector(  970): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
,W/ContextImpl( 6295): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ResourcesManager( 6456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6335): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6335): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6335): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6335): Unrecognized profile 2130706433 for video/avc
,I/MultiDex( 6456): VM with version 2.1.0 has multidex support
I/MultiDex( 6456): install
I/MultiDex( 6456): VM has multidex support, MultiDex support library is disabled.
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 8
W/VideoCapabilities( 6335): Unrecognized profile 2130706433 for video/avc
E/WifiTrafficPoller(  970):  packet count Tx=125 Rx=116
,D/Process (  970): killProcessQuiet, pid=4975
I/ActivityManager(  970): Killing 4975:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  970): Recipient 4975,
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
,I/System.out( 6276): isCompatible false,
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,I/vclib   ( 6335): onServiceConnected,
,W/Babel   ( 6335): Attempted to change video mute state without an active call.,
V/JNIHelp ( 6456): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/libc    ( 6335): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6335): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6335): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6335): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6335): [NET] android_getaddrinfo_proxy+
D/libc    ( 6335): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/ActivityThread( 6456): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6456): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23511209: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ActivityManager(  970): Killing 4539:com.htc.club/u0a181 (adj 15): empty #17
I/ProviderInstaller( 6456): Installed default security provider GmsCore_OpenSSL
D/Process (  970): killProcessQuiet, pid=4539
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6335): [NET] android_getaddrinfo_proxy-, success
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo,
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6295): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6295): [NET] android_getaddrinfo_proxy+
D/libc    ( 6295): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
,D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
,I/Babel   ( 6335): connection state changed from UNKNOWN to CONNECTED
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6295): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 6295): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  970): Recipient 4539
,I/ActivityManager(  970): Killing 4878:com.htc.mediamanager/u0a28 (adj 15): empty #17,
,D/Process (  970): killProcessQuiet, pid=4878
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6430): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6430): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6430): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6430):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6430):   adb logcat -s GAv4
,D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,W/ContextImpl( 6430): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6430): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  970): Recipient 4878
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
,W/GAv4    ( 6430): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6430): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6430): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Icing   ( 4218): Indexing 45DF604A3178D15E8C0610E8DC9A22B2315E4983 from com.google.android.gms
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,W/global  ( 6430): [apache-http] Connection GC has been deprecated!
,W/global  ( 6430): [apache-http] Connection GC has been deprecated!,
,I/WVCdm   (  405): CdmEngine::OpenSession,
I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg,
,I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
,D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
D/QSEECOMAPI: (  405): Loaded image: APP id = 6,
D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49e8000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49e8000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/GoogleURLConnFactory( 6456): Using platform SSLCertificateSocketFactory
,D/DrmLibTime(  539): got the req here! ret=0
D/DrmLibTime(  539): command id, time_cmd_id = 770
D/DrmLibTime(  539): time_getutcsec starts!
D/DrmLibTime(  539): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  539): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  539): QSEE Time Listener: time_get_modem_time,
D/DrmLibTime(  539): QSEE Time Listener: Checking if ATS_MODEM is set or not.
,E/QC-time-services(  539): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  539): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  539): QSEE Time Listener: Retrieved Android system time: 1457599075
D/DrmLibTime(  539): time_getutcsec returns 0, sec = 1457599075; nsec = 0
D/DrmLibTime(  539): time_getutcsec finished! 
D/DrmLibTime(  539): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  539): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,I/Icing   ( 4218): Indexing done 45DF604A3178D15E8C0610E8DC9A22B2315E4983
,D/PMS     (  970): releaseWL(132c84e7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/libc    ( 6456): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 6456): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6456): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6456): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6456): [NET] android_getaddrinfo_proxy+
D/libc    ( 6456): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6456): [NET] android_getaddrinfo_proxy-, success
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4b18928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xaacfb708, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaad11138, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xaad1dc58, idLength=0xf4c186f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=169 Rx=153
,D/libc    ( 6456): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 6456): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6456): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 6456): [NET] android_getaddrinfofornet-, err=8
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1,
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4c1870e, maximum = 0xf4c1870f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9,
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4c1877c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=241792009
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaad0d560
,D/DrmWidevineDash(  405): message_length=1610, signature=0xaad1e1d8, signature_length=0xf4c186dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/WebViewFactory( 6430): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6430): Time to load native libraries: 26 ms (timestamps 3982-4008)
,I/LibraryLoader( 6430): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6430): Binding Chromium to main looper Looper (main, tid 1) {26f8a828}
,I/LibraryLoader( 6430): Expected native library version number "",actual native library version number ""
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/chromium( 6430): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 6,
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
,I/BrowserStartupController( 6430): Initializing chromium process, singleProcess=true
,W/art     ( 6430): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6430): ApplicationContext is null in ApplicationStatus,
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,W/chromium( 6430): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6430): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6430): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6430): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6430): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6430): Local Branch: 
I/Adreno-EGL( 6430): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6430): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6430):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6430): Requires BLUETOOTH permission
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 6430): Starting up...
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
,D/Process (  970): killProcessQuiet, pid=5803
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6550 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Killing 5803:com.htc.widget.hmsproc3/u0a34 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5803
,D/Messaging( 6375): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6375): networkCode: 
D/MessageCustFlag( 6375): sku_id=118
,D/MmsConfig( 6375): SIE smsPri: null
D/MmsConfig( 6375): networkCode: 
,D/MmsConfig( 6375): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6375): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 6375): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6375): 
D/MmsAsyncWorkHandler( 6375): HM tk = 20001
D/ReportIndicatorCache( 6375): MSG_QUERY_REPORTS >>
D/SettingsManager( 6375): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2934b6bd
D/DraftCache( 6375): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6375): [DraftCache/1] refresh
I/Messaging( 6375): mccmnc> 
,D/MmsConfig( 6375): networkCode: 
,D/Messaging( 6375): ViewCache CreatePreloadOnlyConversationList,
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63,
D/AccFlag ( 1489): sku_id=118
,D/DraftCache( 6375): [DraftCache/156] rebuildCache
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1489):  slotId = -1000
D/MmsSmsV2Provider( 1489): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 6375): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 6375): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6375): createReceiver
D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1489):  slotId = -1000
D/MmsSmsV2Provider( 1489): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 6375): sense_version=6.0
D/Jerry   ( 6375): start to preload cursor >>>>>>>
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/Jerry   ( 1489): URI_DRAFT
D/TelephUtils( 1489): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1489): Update uri=content://mms, match=0
V/MmsProvider( 1489): selection=st=129 AND m_type!=134
D/Messaging( 6375): Reset downloading state: 0
V/MmsSystemEventReceiver( 6375): TransactionService is going to be woken up.
D/DraftCache( 6375): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6375): [DraftCache/156] rebuildCache time: 6
D/MmsAsyncWorkHandler( 6375): 
D/MmsAsyncWorkHandler( 6375): HM tk = 20002
V/TransactionService( 6375): 1-Creating TransactionService
D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1489):  slotId = -1000
D/MmsSmsV2Provider( 1489): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6375): mNeedToUpdateDate2: false
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1489):  slotId = -1000
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1489):  slotId = -1000
D/MmsSmsV2Provider( 1489): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1489): sku_id=118
,D/Messaging( 6375): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 6375): ViewCache CreatePreload
D/Messaging( 6375): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6375): onStartCommand: 1
D/MmsSystemEventReceiver( 6375): unRegisterForConnectionStateChanges
,V/TransactionService( 6375): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6375): Loading previous transactions.
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/AccFlag ( 1489): sku_id=118
,D/TelephUtils( 1489): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/Cust_MMSMS( 6375): _has_set_default_values_2=true
D/AccFlag ( 1489): device_type: 1
,D/TransactionService( 6375): Force clearing mTransactionList,
D/TransactionService( 6375): Force set service start id to 1
V/TransactionService( 6375): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6375): unRegisterForConnectionStateChanges
D/TransactionService( 6375): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6375): Destroying TransactionService
D/MsgPreferenceUtils( 6375): def_index: 0
,V/TransactionService( 6375): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
D/MsgPreferenceUtils( 6375): globalIndex = 1
,D/MsgPreferenceUtils( 6375): phone state: true
,D/MsgPreferenceUtils( 6375): sd state: false
D/MsgPreferenceUtils( 6375): vIndex = 0
,E/cutils-trace( 6587): Error opening trace file: Permission denied (13)
I/dex2oat ( 6587): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6587): dex2oat: override thread count:4
,I/dex2oat ( 6587): dex2oat took 52.214ms (threads: 4)
,I/Adreno-EGL( 6456): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6456): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6456): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6456): Local Branch: 
I/Adreno-EGL( 6456): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6456): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6456):                  d74aa161a12b9c6fc6332151
,D/Process (  970): killProcessQuiet, pid=5895,
I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6603 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  970): Killing 5895:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
,I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/Adreno-EGL( 6456): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6456): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6456): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6456): Local Branch: 
I/Adreno-EGL( 6456): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6456): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6456):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  970): Recipient 5895,
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.identity/versions/887a7f5610a36712ed50f1fb1911e4b5da8368ea/cid/MDoyOjIwMTUtMTItMjNUMDM6MjM6MTIuMzY4Wg,
,I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6276): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6276): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6276): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6276): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
D/libc    ( 6276): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6276): [NET] android_getaddrinfo_proxy+,
D/libc    ( 6276): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6276): [NET] android_getaddrinfo_proxy-, success
,W/ResourcesManager( 6603): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6295): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6295): [NET] android_getaddrinfo_proxy+
D/libc    ( 6295): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6295): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 6295): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 8,
I/HtcModeClient( 3162): handler message = 4011
E/HtcModeClient( 3162): Check connection and retry 11 times.
E/WifiTrafficPoller(  970):  packet count Tx=220 Rx=204
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=48.8, 0.0, 0.0  rx=47.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1605163618] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=48.8, 0.0, 0.0  rx=47.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605163620] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=6 [131][8][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=89.41 txretriesrate=0.00 rxrate=81.62 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
,I/WVCdm   (  405): CdmEngine::OpenSession
,I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
,E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
,D/PMS     (  970): releaseWL(2e597d0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
D/PMS     (  970): acquireWL(29af5152): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  970): killProcessQuiet, pid=5387
,I/ActivityManager(  970): Killing 5387:com.android.settings/1000 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/QSEECOMAPI: (  405): Loaded image: APP id = 7,
,D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49e8000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49e8000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  539): got the req here! ret=0
D/DrmLibTime(  539): command id, time_cmd_id = 770
,D/DrmLibTime(  539): time_getutcsec starts!
D/DrmLibTime(  539): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  539): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  539): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  539): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  539): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  539): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  539): QSEE Time Listener: Retrieved Android system time: 1457599077
D/DrmLibTime(  539): time_getutcsec returns 0, sec = 1457599077; nsec = 0
D/DrmLibTime(  539): time_getutcsec finished! 
D/DrmLibTime(  539): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  539): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/PMS     (  970): releaseWL(29af5152): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/PMS     (  970): acquireWL(21d8cc23): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!,
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4c18928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xaacf3c38, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaad0f8c0, wrapped_rsa_key_length=1280
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xaad1dc98, idLength=0xf4b186f8
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b1870e, maximum = 0xf4b1870f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b1877c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=2513912255
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaace2fb8
D/DrmWidevineDash(  405): message_length=1642, signature=0xaad1e1d8, signature_length=0xf4b186dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,I/ActivityManager(  970): Recipient 5387
,D/WifiService(  970): Client connection lost with reason: 4
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pns/versions/55580870d4ecef7adc0bfac442bc01d880550489/cid/MDoxOjIwMTQtMTAtMjNUMDI6MDc6MTQuNTA0Wg
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!,
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
,V/BluetoothSapService( 5769): onUnbind,
,D/PMS     (  970): acquireWL(35e2077f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10176 com.google.android.youtube},
,I/CheckinRequestBuilder( 4218): Classify the device as Phone.
,D/PMS     (  970): releaseWL(21d8cc23): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6645 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/PMS     (  970): releaseWL(35e2077f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  970): acquireWL(22718f95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
D/Process (  970): killProcessQuiet, pid=5411,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  970): Killing 5411:com.android.vending/u0a72 (adj 15): empty #17
,D/PMS     (  970): releaseWL(22718f95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(2657b8aa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Recipient 5411
,D/Process (  970): killProcessQuiet, pid=5990
I/ActivityManager(  970): Killing 5990:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PMS     (  970): acquireWL(b199c9b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10176 com.google.android.youtube}
,I/ActivityManager(  970): Recipient 5990
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
,I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,D/PMS     (  970): acquireWL(19a89011): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 6169 10069 null
D/PMS     (  970): releaseWL(b199c9b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
D/PMS     (  970): acquireWL(6d0b576): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 6169 10069 null
,D/PMS     (  970): acquireWL(d6b6777): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 6169 10069 null,
D/PMS     (  970): releaseWL(2657b8aa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2d4b7fe4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(19a89011): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  970): acquireWL(6d0b576): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 6169 10069 null
,D/PMS     (  970): releaseWL(d6b6777): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  970): releaseWL(2d4b7fe4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(90ab302): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/ProviderChangeReceiver( 6065): ---------------------------------------------------,
D/ProviderChangeReceiver( 6065): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,E/TodoTaskNotifyService( 6169): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 6169): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 6169): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,D/PMS     (  970): releaseWL(6d0b576): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 6169): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 6169): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6169): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 6169): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 6169): stopSelfResult true
D/HtcAlertService( 6065): start to updateAlertNotification!
,D/PMS     (  970): releaseWL(90ab302): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcAlertService( 6065): No fired or scheduled alerts
D/HtcAlertUtils( 6065): -- cancelReminderNotification --
D/HtcAlertUtils( 6065): broadcastExistReminder!
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  970): acquireWL(11a50413): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=233 rxSum=215} preTxRxSum={txSum=77 rxSum=75}
D/PMS     (  970): acquireWL(432b650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=251 Rx=234
,D/PMS     (  970): acquireWL(f043049): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  970): releaseWL(432b650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo
,I/DeviceManagement( 6276): DeviceClientResource: Active network...
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PMS     (  970): releaseWL(11a50413): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4,
,D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  970): acquireWL(21d1ce6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(21d1ce6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1913): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4218): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4218, uid=10024, userID:0,
,I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6676 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/LocationInitializer( 4218): Restart initialization of location
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=6697 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,W/ResourcesManager( 6676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  970): releaseWL(f043049): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
D/PMS     (  970): acquireWL(22cf1c67): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(22cf1c67): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(b80aa14): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/MultiDex( 6676): VM with version 2.1.0 has multidex support
,I/MultiDex( 6676): install
I/MultiDex( 6676): VM has multidex support, MultiDex support library is disabled.
,D/PMS     (  970): acquireWL(3912b2bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/SMSBackup( 6697): Got a database change event
,V/JNIHelp ( 6676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6676): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23511209: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6676): Installed default security provider GmsCore_OpenSSL
,I/art     (  970): Explicit concurrent mark sweep GC freed 28456(1352KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.523ms total 139.979ms,
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  970): releaseWL(b80aa14): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4218): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4218): [NET] android_getaddrinfo_proxy+
D/libc    ( 4218): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/WearableService( 6676): callingUid 10024, callindPid: 6676,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1824): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/PMS     (  970): acquireWL(1b6b6af1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5971 10159 null,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4218): [NET] android_getaddrinfo_proxy-, success
,E/Ads     ( 4218): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication,
,D/PMS     (  970): releaseWL(3912b2bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(234c6ce5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(234c6ce5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: [],
I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false,
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5971, uid=10159, userID:0,
,D/PMS     (  970): releaseWL(1b6b6af1): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 5971): Conditions not met for autocaching. okToAttempt=false,
I/MusicLeanback( 5971): Stop autocaching.
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
,E/GmsUtils( 5971): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
I/DeviceManagement( 6276): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/DeviceManagement( 6276): DeviceClientResource: Active network...,
I/DeviceManagement( 6276):   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/GmsUtils( 5971): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  970): killProcessQuiet, pid=6021
,I/ActivityManager(  970): Killing 6021:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  970): acquireWL(2442da47): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 6276): [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
D/libc    ( 6276): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4218): Sending checkin request (10210 bytes),
I/ActivityManager(  970): Recipient 6021
,D/PMS     (  970): releaseWL(2442da47): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(28e2c274): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(28e2c274): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1984539d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1984539d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(373fa012): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(373fa012): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1913): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4218): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1824): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4218, uid=10024, userID:0
,D/PMS     (  970): acquireWL(32a391e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/LocationInitializer( 4218): Restart initialization of location,
,D/PMS     (  970): releaseWL(32a391e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=292 Rx=266
,I/DeviceManagement( 6276): DMServiceClientResourceController: handleDirectives: [],
,I/DeviceManagement( 6276): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 6276): DeviceClientResourceController: handleDirectives: []
I/System.out( 6276): isCompatible false
I/System.out( 6276): createObjectMapper
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false,
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
I/System.out( 6276): isCompatible false
,I/DeviceManagement( 6276): ConfigCacheController: *** Update config cache: updating 8 entries...,
I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>,
,I/CheckinResponseProcessor( 4218): From server: 11 gservices updates and 1 deletes
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>,
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, statusCode=0, authCode=0>,
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, statusCode=0, authCode=0>
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 6276): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>,
,I/DeviceManagement( 6276): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 6276): AlarmController: Scheduling TTL alarm for: 2016.03.11 at 09:37:59.000 CET (due to: com.htc.launcher),
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=6276, uid=10099, userID:0,
,I/DeviceManagement( 6276): Perf: *** Config cache update - complete: 5116 ms,
,I/DeviceManagement( 6276): Perf: *** Cache update - complete: 5122 ms
,I/DeviceManagement( 6276): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@e02bc03],
,I/DeviceManagement( 6276): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4d6c052] args=[Bundle[mParcelledData.dataSize=88]]
I/DeviceManagement( 6276): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
I/DeviceManagement( 6276): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6276): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6276): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6276): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4d6c052],
,I/DeviceManagement( 6276): WorkflowService: Stopping workflow service
,D/Process (  970): killProcessQuiet, pid=6098,
I/ActivityManager(  970): Killing 6098:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CertBlacklister(  970): Certificate blacklist changed, updating...,
,I/CertBlacklister(  970): Certificate blacklist updated
,I/GservicesProvider( 1913): main difference update completed
,I/PushClient( 6144): PnsModel {37fb01b9}: update(): Start updating since the registration has expired.
,I/ActivityManager(  970): Recipient 6098,
,W/PushClient( 6144): GCMRegistrator {13c677e3}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
W/PushClient( 6144):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6144):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6144):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6144):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6144):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:372)
W/PushClient( 6144):   	at com.htc.cs.pns.receiver.OnConnectedHandler.handle(OnConnectedHandler.java:31)
W/PushClient( 6144):   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.handleBroadcast(AbstractIntentServiceBroadcastReceiver.java:123)
W/PushClient( 6144):   	at com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver$HandleBroadcastServiceImpl.handleBroadcast(OneTimeOnConnectedReceiver.java:33)
W/PushClient( 6144):   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.onHandleIntent(AbstractIntentServiceBroadcastReceiver.java:94)
W/PushClient( 6144):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6144):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6144):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6144):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6144):   
,I/ActivityManager(  970): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6742 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/CheckinRequestBuilder( 4218): Checkin reason type: 8 attempt count: 1,
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4218): Failed to find provider info for com.google.android.wearable.settings
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=6742, uid=10027, userID:0
,D/PMS     (  970): acquireWL(1e73c836): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1e73c836): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 37261(1973KB) AllocSpace objects, 9(372KB) LOS objects, 46% free, 4MB/8MB, paused 1.127ms total 62.995ms,
I/ActivityManager(  970): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6777 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
I/art     (  430): Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 185us total 20.980ms
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 155us total 18.721ms
D/PMS     (  970): acquireWL(e10e337): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(e10e337): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 151us total 17.888ms
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): acquireWL(160fa80e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(160fa80e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
W/CheckinRequestBuilder( 4218): awaiting user notification for token
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4218): Classify the device as Phone.
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=305 Rx=278
,I/art     (  970): Explicit concurrent mark sweep GC freed 16308(768KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.474ms total 143.508ms,
,D/PMS     (  970): acquireWL(32b3022f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(32b3022f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinTask( 4218): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,E/UpdateRequestReceiver( 6777): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 4218): Checking schedule, now: 1457599079907 next: 1458135911891,
I/CheckinService( 4218): active receiver: disabled
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4218, uid=10024, userID:0
,D/PMS     (  970): acquireWL(e5641c5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(e5641c5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/UpdateFetcherService( 6777): Update started
,D/PMS     (  970): acquireWL(622371a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,E/UpdateRequestReceiver( 6777): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/PMS     (  970): acquireWL(3f7e5428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3f7e5428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4218): Checking schedule, now: 1457599079951 next: 1458135911891
I/CheckinService( 4218): active receiver: disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4218, uid=10024, userID:0
,E/UpdateRequestReceiver( 6777): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/PMS     (  970): releaseWL(31ff9479): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=89.4, 0.0, 0.0  rx=81.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1605166628] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState,
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=89.4, 0.0, 0.0  rx=81.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1605166629] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=5 [75][4][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=82.20 txretriesrate=0.00 rxrate=74.81 userTriggerdPenalty0
,E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  970): acquireWL(55e3541): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2e9caae6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(55e3541): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/UpdateRequestReceiver( 6777): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  970): Killing 5837:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=5837
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 6144): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 4
D/libc    ( 6144): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6144): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
D/libc    ( 6144): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6144): [NET] android_getaddrinfo_proxy+
D/libc    ( 6144): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/PMS     (  970): acquireWL(22788ad4): PARTIAL_WAKE_LOCK  DownloadManager 0x1 3591 10017 WorkSource{10098},
,D/DownloadManager( 3591): [32] Starting,
,D/libc    ( 3591): [NET] android_getaddrinfofornet+,hn 15(0x7777772e677374),sn(),hints(known),family 0,flags 4,
D/libc    ( 3591): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 3591): [NET] android_getaddrinfofornet+,hn 15(0x7777772e677374),sn(),hints(known),family 0,flags 1024
D/libc    ( 3591): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 3591): [NET] android_getaddrinfo_proxy+
D/libc    ( 3591): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 15(0x7777772e677374),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  970): Recipient 5837
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 3591): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    ( 6144): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(15b5ffc3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{17c8c61d: PendingIntentRecord{24476092 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=98129, Int=0
D/PMS     (  970): releaseWL(622371a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/Process (  970): killProcessQuiet, pid=6194
I/ActivityManager(  970): Killing 6194:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/DownloadManager( 3591): [32] Finished with status SUCCESS,
,I/ActivityManager(  970): Recipient 6194,
,I/VacuumService( 1913): Vacuum at: now=1457599080333 tag=VacuumService
,D/PMS     (  970): releaseWL(22788ad4): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10098}
D/PMS     (  970): acquireWL(abc30be): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(49a606c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4218 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(abc30be): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=4218, uid=10024, userID:0,
D/PMS     (  970): releaseWL(15b5ffc3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/CheckinService( 4218): Checking schedule, now: 1457599080377 next: 1458135911891,
I/CheckinService( 4218): active receiver: disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4218, uid=10024, userID:0,
,I/SystemUpdateService( 4218): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver },
,D/PMS     (  970): acquireWL(3ea42635): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4218): onCreate
D/SystemUpdateService( 4218): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/PMS     (  970): releaseWL(49a606c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1913): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/SystemUpdateService( 4218): cancelUpdate (empty URL)
I/SystemUpdateService( 4218): active receiver: disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4218, uid=10024, userID:0
,D/PMS     (  970): releaseWL(2e9caae6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(13db9996): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/SystemEventReceiver( 4218): Received GSERVICES_CHANGED broadcast,
,I/OcrUtils( 4218): Updating ocr activity enabled=false
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=4218, uid=10024, userID:0
,D/PMS     (  970): releaseWL(3ea42635): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4218): onDestroy
,I/GCoreUlr( 1824): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/PMS     (  970): releaseWL(13db9996): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(344fe6ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(344fe6ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1824): DispatchingService.onCreate()
,D/PMS     (  970): acquireWL(12d17970): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.copresence.service.ProximitySettingInjectorService, state=2, flag=1, pid=1824, uid=10024, userID:0
,I/GCoreUlr( 1824): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 4218): Explicit concurrent mark sweep GC freed 33192(2MB) AllocSpace objects, 13(260KB) LOS objects, 40% free, 7MB/12MB, paused 1.191ms total 68.645ms
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 12539(655KB) AllocSpace objects, 3(252KB) LOS objects, 46% free, 4MB/8MB, paused 995us total 40.037ms
,I/PushClient( 6144): PnsModel {37fb01b9}: update(): Update registration succeeded.,
I/GCoreUlr( 1824): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  970): acquireWL(32d104e9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms},
D/Process (  970): killProcessQuiet, pid=6224
I/ActivityManager(  970): Killing 6224:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=322 Rx=294
,I/ActivityManager(  970): Recipient 6224
,D/PMS     (  970): releaseWL(32d104e9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1824): Unbound from all location providers
,D/PMS     (  970): releaseWL(12d17970): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1824): DispatchingService.onDestroy()
,D/PMS     (  970): acquireWL(7b4456e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(7b4456e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1824): Unbound from all location providers
,D/PMS     (  970): acquireWL(3a2cbc9c): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,E/Icing   ( 4218): Loading extension by file descriptor -1 failed
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1824, uid=10024, userID:0,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1913, uid=10024, userID:0,
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6838 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/PMS     (  970): releaseWL(3a2cbc9c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(18970688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null,
I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  970): acquireWL(117b6821): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 970 1000 WorkSource{10024}
D/PMS     (  970): releaseWL(18970688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  970): acquireWL(351caed2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null,
,D/PMS     (  970): releaseWL(351caed2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1223): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  970): acquireWL(22e69ba3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(117b6821): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
D/PMS     (  970): releaseWL(22e69ba3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/LocationManagerService(  970): getProviders()=[passive]
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5686): 
,D/Process (  970): killProcessQuiet, pid=6144,
I/ActivityManager(  970): Killing 6144:com.htc.cs.pns/u0a71 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 6144,
,V/SetupWizard( 6254): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GservicesUpdateTask( 6838): Updating Gservices keys
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 5686): 
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 4502(183KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 780us total 41.997ms
,I/Kids    ( 4218): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,V/ConfigFetchTask( 4218): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WZz7O5oNxXTAlhf1mMe8BBrzKsGYje4K_JTMl6_5kktfjsaqviIg7obF9iwnB-clko771VhflShMNFn_n0KDxsFVS7zKpwKFB3nR0H8WGQ2MfNSUiNgxKv5UV8tomYr8jwvn6hCXsnB9wbLhZsysb1kQs2wGhLHKSMNiJX3m8qJijx7wZsWA7vA34iTk7S8deZWGbVbzzp4lac_FO5rzybiWzxm7BoGvjMpvRiusslxbioNOc,
,I/GoogleURLConnFactory( 4218): Using platform SSLCertificateSocketFactory
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4218): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4218): [NET] android_getaddrinfo_proxy+
D/libc    ( 4218): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4218): [NET] android_getaddrinfo_proxy-, success
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 5686): 
,I/art     (  970): Explicit concurrent mark sweep GC freed 16422(908KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/24MB, paused 1.792ms total 136.300ms
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4218): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4218): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PMS     (  970): acquireWL(2e3d9b91): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=333 Rx=302
,D/PMS     (  970): releaseWL(2e3d9b91): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(18c79af6): PARTIAL_WAKE_LOCK  DownloadManager 0x1 3591 10017 WorkSource{10098},
,D/DownloadManager( 3591): [33] Starting
,I/HtcModeClient( 3162): handler message = 4011,
E/HtcModeClient( 3162): Check connection and retry 12 times.
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 5686): 
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 4218): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5686): 
D/libc    ( 4218): [NET] android_getaddrinfofornet-, err=8
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 5686): 
,D/DownloadManager( 3591): [33] Finished with status SUCCESS
,D/PMS     (  970): releaseWL(18c79af6): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10098},
,I/UpdateFetcherService( 6777): Update downloaded, starting installation,
,I/UpdateFetcherService( 6777): doneInstall,
,I/ConfigUpdateInstallReceiver(  970): Found new update, installing...
,I/ConfigUpdateInstallReceiver(  970): Installation successful
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 5686): 
,I/ConfigFetchTask( 4218): updating config table for com.google.android.gms,
,I/ConfigFetchService( 4218): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver },
,D/PMS     (  970): acquireWL(1f85b393): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4218 10024 null,
I/ConfigFetchService( 4218): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 4218): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 4218): fetch service done; releasing wakelock
D/PMS     (  970): releaseWL(19355c6d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(4bc97b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1f566fd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/ConfigFetchService( 4218): self-hosted config:fetch_interval = 43200,
,D/PMS     (  970): releaseWL(1f566fd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(38bf2bc9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
I/ConfigFetchService( 4218): stopping self
,D/PMS     (  970): releaseWL(1f85b393): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  970): releaseWL(38bf2bc9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
I/jxcore-log( 5686): 
,I/ActivityManager(  970): Killing 6430:com.google.android.apps.magazines/u0a161 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6430
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6430
,I/ClockController( 1223): schedule update now=1457599082413 next=57587,
,I/Clock   ( 1223): updateClock:09:38 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:38 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:38 Europe/Warsaw
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=331 rxSum=297} preTxRxSum={txSum=233 rxSum=215}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=352 Rx=321
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=82.2, 0.0, 0.0  rx=74.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1605169638] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=82.2, 0.0, 0.0  rx=74.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605169640] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=2 [45][1][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150,
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=63.60 txretriesrate=0.00 rxrate=56.91 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1684): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1684): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1537): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/[PluginManager]RegisterService( 1449): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1449): handle notify Blinkfeed plugin client changed
W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Launcher( 1537): Deferring update until onResume
I/ActivityManager(  970): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6893 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Launcher( 1537): waitUntilResume // bindAppsUpdated
,D/PhoneApp( 1489): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1684): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1684): Unsupported attribute readOnly
,D/PhoneApp( 1489): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,D/AccTypeManager( 1684): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1684): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1684): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  970): Killing 6550:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6550
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneApp( 1489): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1684): Unsupported attribute readOnly,
,W/PackageManager(  970): Unable to load service info ResolveInfo{12d1f706 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/AccTypeManager( 1684): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1684): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1684): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1684): Unsupported attribute readOnly
,I/ActivityManager(  970): Recipient 6550,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6893): -onCreate()
,V/Settings:HtcSettingsApplication( 6893): [6893/6893] onCreate(),
,W/PackageManager(  970): Unable to load service info ResolveInfo{16b37820 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  970): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6915 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Killing 6375:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6375
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,D/Settings:HtcWirelessFeatureFlags( 6893): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 6893): no such activity!,
,I/ActivityManager(  970): Recipient 6375,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6893): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 6893): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 6893): isSupportMusicChannel(): false,
,W/PackageManager(  970): Unable to load service info ResolveInfo{2ac5dc57 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): ,	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]support         :false
V/GmsNetworkLocationProvi( 1824): DISABLE
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]support         :false
,I/GCoreNlp( 1824): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  970): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6893): isSupportVoWifi: null
E/ActivityThread( 6893): Failed to find provider info for com.htc.vowifi
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=353 Rx=322
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6893): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 6893): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6893): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6893): [supportHomeButton]support         :false
,D/PMS     (  970): acquireWL(3dc30279): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(3dc30279): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/LocationProviderProxy(  970): applying state to connected service
I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi,
D/LocationProviderProxy(  970): applying state to connected service
E/ActivityThread( 6893): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6893): isSupportVoWifi: null
D/PMS     (  970): acquireWL(195f1bbe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1bdd87b1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1bdd87b1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(195f1bbe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6915, uid=10072, userID:0,
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 4,
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 1024
D/libc    ( 6295): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6295): [NET] android_getaddrinfo_proxy+
D/libc    ( 6295): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 1024,
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/global  ( 6915): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 6915): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 6915): [apache-http] Connection GC has been deprecated!
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6295): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 6295): [NET] android_getaddrinfofornet-, SUCCESS
,W/global  ( 6915): [apache-http] Connection GC has been deprecated!,
,D/libc    ( 6295): [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 4,
D/libc    ( 6295): [NET] android_getaddrinfofornet-, err=8
,D/Finsky  ( 6915): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  970): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6959 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 6915): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6915): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6915, uid=10072, userID:0,
,W/ResourcesManager( 6959): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6959): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6915): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 6915): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 6959): VM with version 2.1.0 has multidex support,
I/MultiDex( 6959): install
I/MultiDex( 6959): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6915): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 6959): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 4218): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,D/Finsky  ( 6915): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,D/PMS     (  970): acquireWL(8755988): PARTIAL_WAKE_LOCK  AsyncService 0x1 6603 10167 null
,D/PMS     (  970): acquireWL(7245507): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,W/ActivityThread( 6959): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6959): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23511209: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6959): Installed default security provider GmsCore_OpenSSL
D/PMS     (  970): acquireWL(26ca8634): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6603 10167 null
,D/PMS     (  970): releaseWL(8755988): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  970): releaseWL(7245507): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/PeopleContactsSync( 4218): CP2 sync disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4218, uid=10024, userID:0
,I/UpdateIcingCorporaServi( 6838): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,I/[PluginManager]RegisterService( 1449): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.pns
I/[PluginManager]RegisterService( 1449): handle notify Blinkfeed plugin client changed
,D/PMS     (  970): releaseWL(26ca8634): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PackageBroadcastService( 4218): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.pns,
,D/PMS     (  970): acquireWL(2ee8ddff): PARTIAL_WAKE_LOCK  AsyncService 0x1 6603 10167 null,
D/PMS     (  970): releaseWL(2ee8ddff): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/PeopleContactsSync( 4218): CP2 sync disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4218, uid=10024, userID:0
,D/PMS     (  970): acquireWL(3a33612a): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(3ff75b1b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6603 10167 null
,D/PMS     (  970): releaseWL(3a33612a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3ff75b1b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,D/PMS     (  970): acquireWL(2bf634b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6335 10112 null
,I/[PluginManager]RegisterService( 1449): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1449): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4218): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4218): Null package name or gms related package.  Ignoreing.,
,W/ResourcesManager( 6335): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6335): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  970): releaseWL(2bf634b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  970): acquireWL(1b183dce): PARTIAL_WAKE_LOCK  Icing 0x1 4218 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4218): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  970): acquireWL(207e68da): PARTIAL_WAKE_LOCK  AsyncService 0x1 6603 10167 null
,D/PMS     (  970): releaseWL(207e68da): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  970): acquireWL(bc3be8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6603 10167 null
,I/UpdateIcingCorporaServi( 6838): UpdateCorporaTask done [took 175 ms] updated apps [took 175 ms] 
I/UpdateIcingCorporaServi( 6838): Updating corpora: APPS=com.htc.cs.pns, CONTACTS=MAYBE
,D/GCM     ( 1913): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/PMS     (  970): releaseWL(bc3be8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
D/PMS     (  970): releaseWL(1b183dce): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/AuthorizationBluetoothService( 1913): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4218): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/UpdateIcingCorporaServi( 6838): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
,I/UpdateIcingCorporaServi( 6838): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4218, uid=10024, userID:0
,D/WearableService( 6676): callingUid 10024, callindPid: 6676
,D/LocationInitializer( 4218): Restart initialization of location
,E/MDM     ( 1824): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/UpdateIcingCorporaServi( 6838): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
,V/Finsky  ( 6915): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,V/JNIHelp ( 6335): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b +
I/Prism.WidgetManager( 1537): onLoadItems() +
,W/ResourcesManager( 1537): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/System  ( 6335): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6335): Installed default security provider GmsCore_OpenSSL,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
,E/WifiTrafficPoller(  970):  packet count Tx=364 Rx=342
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): acquireWL(1eb4b9a9): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072},
V/AlarmManager(  970): sending alarm PendingIntent{253abb2e: PendingIntentRecord{e9d4b49 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457599085326, Int=0
D/PMS     (  970): releaseWL(1eb4b9a9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 6915): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ResourcesManager( 1537): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6915): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  970): Explicit concurrent mark sweep GC freed 33970(1903KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.865ms total 178.975ms
,E/Babel   ( 6335): UserRecoverableAuthException.
E/Babel   ( 6335): eei: BadAuthentication
E/Babel   ( 6335): 	at eeg.a(Unknown Source)
E/Babel   ( 6335): 	at eeg.a(Unknown Source)
E/Babel   ( 6335): 	at eeg.a(Unknown Source)
E/Babel   ( 6335): 	at g.a(Unknown Source)
E/Babel   ( 6335): 	at cae.a(SourceFile:3089)
E/Babel   ( 6335): 	at cae.a(SourceFile:1131)
E/Babel   ( 6335): 	at cws.a(SourceFile:4333)
E/Babel   ( 6335): 	at cws.a(SourceFile:1419)
E/Babel   ( 6335): 	at crl.a(SourceFile:492)
E/Babel   ( 6335): 	at crl.a(SourceFile:1468),
E/Babel   ( 6335): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6335): 	at cas.b(SourceFile:106)
E/Babel   ( 6335): 	at cap.d(SourceFile:335)
E/Babel   ( 6335): 	at caq.run(SourceFile:81)
E/Babel   ( 6335): Error getting auth token
E/Babel   ( 6335): dvm
E/Babel   ( 6335): 	at g.a(Unknown Source)
E/Babel   ( 6335): 	at cae.a(SourceFile:3089)
E/Babel   ( 6335): 	at cae.a(SourceFile:1131)
E/Babel   ( 6335): 	at cws.a(SourceFile:4333)
E/Babel   ( 6335): 	at cws.a(SourceFile:1419)
E/Babel   ( 6335): 	at crl.a(SourceFile:492)
E/Babel   ( 6335): 	at crl.a(SourceFile:1468)
E/Babel   ( 6335): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6335): 	at cas.b(SourceFile:106)
E/Babel   ( 6335): 	at cap.d(SourceFile:335)
E/Babel   ( 6335): 	at caq.run(SourceFile:81)
,E/Babel   ( 6335): Account registration failed 1-Redacted-21
E/Babel   ( 6335): cyp: null -- null
E/Babel   ( 6335): 	at cae.a(SourceFile:3121)
E/Babel   ( 6335): 	at cae.a(SourceFile:1131)
E/Babel   ( 6335): 	at cws.a(SourceFile:4333)
E/Babel   ( 6335): 	at cws.a(SourceFile:1419)
E/Babel   ( 6335): 	at crl.a(SourceFile:492)
E/Babel   ( 6335): 	at crl.a(SourceFile:1468)
E/Babel   ( 6335): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6335): 	at cas.b(SourceFile:106)
E/Babel   ( 6335): 	at cap.d(SourceFile:335)
E/Babel   ( 6335): 	at caq.run(SourceFile:81)
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/asset   ( 1537): Copying FileAsset 0x5566a19f40 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,I/art     ( 6335): Note: end time exceeds epoch: 
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1913): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM
D/PMS     (  970): acquireWL(253e77c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
V/AlarmManager(  970): sending alarm PendingIntent{176ebaad: PendingIntentRecord{5d461e2 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1457599085583, Int=20000
E/WifiStateMachine(  970): processMsg: ConnectedState
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:8386 rssi=-46 f=2442 sc=60 link=150 tx=63.6, 0.0, 0.0  rx=56.9 fiv=60000 [on:0 tx:0 rx:0 period:2583] from screen [on:0 period:1605172241]
D/PMS     (  970): releaseWL(253e77c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:8386 rssi=-46 f=2442 sc=60 link=150 tx=63.6, 0.0, 0.0  rx=56.9 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1605172242]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=63.60 rxSuccessRate=56.91 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=19797 interval=60000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=63.60 rx=56.91
E/WifiStateMachine(  970): handleMessage: X
,W/Finsky  ( 6915): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/Babel   ( 6335): Unexpected exception while authenticating.
,E/Babel   ( 6335): eej: User intervention required. Notification has been pushed.
E/Babel   ( 6335): 	at eeg.b(Unknown Source)
E/Babel   ( 6335): 	at eeg.b(Unknown Source)
E/Babel   ( 6335): 	at g.a(Unknown Source)
E/Babel   ( 6335): 	at cae.b(SourceFile:1146)
E/Babel   ( 6335): 	at dcg.run(SourceFile:5617)
E/Babel   ( 6335): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6335): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6335): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Prism.WidgetManager( 1537): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1537): onLoadItems() -
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b -
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,E/AndroidHttpClient( 6915): Leak found
E/AndroidHttpClient( 6915): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 6915): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 6915): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 6915): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 6915): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 6915): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 6915): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 6915): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 6915): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 6915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 6915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 6915): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 6915): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 6915): 	,at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 6915): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 6915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 6915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/PhoneApp( 1489): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1489): -- N1 =0
,D/PhoneApp( 1489): -- N2 =0,
,D/PhoneApp( 1489): -- N3 =0
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  970): acquireWL(33702e43): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
,V/AlarmManager(  970): sending alarm PendingIntent{1fae4cc0: PendingIntentRecord{35195df9 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457599085828, Int=60000
D/PMS     (  970): releaseWL(33702e43): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6697): SMSBackupAgentService started
,D/SMSBackup( 6697): Checking restore status
D/SMSBackup( 6697): Restore complete
,D/SMSBackup( 6697): cancelCheckAlarm
,D/SMSBackup( 6697): SMSBackupAgentService completed: completed in 0.0 seconds
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6915): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 6915): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 6915): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 6915): [1] DailyHygiene.reschedule: Scheduling new run in 253 minutes (failures=4),
,D/Finsky  ( 6915): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested,
,D/DeviceConnectionService( 1824): client connected with version: 7571000,
,D/Finsky  ( 6915): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=63.6, 0.0, 0.0  rx=56.9 bcn=0 [on:0 tx:0 rx:0 period:415] from screen [on:0 period:1605172658] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=63.6, 0.0, 0.0  rx=56.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605172660] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [14][0][0],
,E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=38.80 txretriesrate=0.00 rxrate=40.95 userTriggerdPenalty0,
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=366 Rx=346
,I/art     ( 4218): Explicit concurrent mark sweep GC freed 30087(1647KB) AllocSpace objects, 3(80KB) LOS objects, 40% free, 7MB/13MB, paused 1.168ms total 111.852ms,
,I/HtcModeClient( 3162): handler message = 4011,
,E/HtcModeClient( 3162): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3162): Don't start project servcice,
D/HtcModeClient( 3162): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3162): connectState: CONNECTION_READY = false
,D/SilentMusic( 3162): call stop
,D/HtcModeClient( 3162): close connection
W/HtcModeClient( 3162): leaveProjectMode: It does not enter ProjectMode,
W/CANMesgAgentLocalSocket( 3162): read the terminate packet, so break
,D/Process (  970): killProcessQuiet, pid=3162,
I/ActivityManager(  970): Killing 3162:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 3162
,I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b +
D/WIFI_ICON( 1223): WifiActivity: 0
I/Prism.WidgetManager( 1537): onLoadItems() +
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=366 Rx=346
,E/WifiTrafficPoller(  970): notifying of data activity 0
I/ConfigService( 1913): onDestroy
,E/Prism.WidgetManager( 1537): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1537): onLoadItems() -
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b -
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=344 rxSum=307} preTxRxSum={txSum=331 rxSum=297},
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  970):  packet count Tx=366 Rx=347
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 1
,I/Prism.ItemManager( 1537): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b +
I/Prism.WidgetManager( 1537): onLoadItems() +
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=38.8, 0.0, 0.0  rx=41.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1605175681] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=38.8, 0.0, 0.0  rx=41.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1605175683] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=19.40 txretriesrate=0.00 rxrate=20.98 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
E/WifiStateMachine(  970): handleMessage: X
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  970):  packet count Tx=366 Rx=347
D/WIFI_ICON( 1223): WifiActivity: 0
,E/WifiTrafficPoller(  970): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/Prism.WidgetManager( 1537): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1537): onLoadItems() -
I/Prism.ItemManager( 1537): loadItems() com.htc.launcher.pageview.WidgetManager@16aebe9b -
,W/PackageSettings(  970): Skipping PackageSetting{2353714f com.example.hello/10374} due to missing metadata,
,D/Process (  970): killProcessQuiet, pid=6065,
I/ActivityManager(  970): Killing 6065:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6065
,D/Process (  970): killProcessQuiet, pid=6169
I/ActivityManager(  970): Killing 6169:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6169,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=367 Rx=348,
D/WIFI_ICON( 1223): WifiActivity: 3
E/WifiTrafficPoller(  970): notifying of data activity 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/Process (  970): killProcessQuiet, pid=6295
,I/ActivityManager(  970): Killing 6295:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6295
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  970):  packet count Tx=371 Rx=351
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=19.4, 0.0, 0.0  rx=21.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1605178702] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=19.4, 0.0, 0.0  rx=21.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1605178703] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [5][0][0]
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=12.20 txretriesrate=0.00 rxrate=14.49 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X,
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -46, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  970):  packet count Tx=371 Rx=357
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  970): notifying of data activity 1
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=349 rxSum=310} preTxRxSum={txSum=344 rxSum=307}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@11105afc
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  970): goingToSleep
W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@11105afc, eanble = 0, strlen(mName) = 91
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1e16b8ce
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@29efbced
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  970): Sleeping (uid 1000)...
D/XAN-DPS (  970): prepareColorFade 1
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
,D/PMS     (  970): acquireWL(3e10b769): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null,
,W/PMS     (  970): mWirelessDisplayManager is null
I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,W/PMN     (  970): goingToSleep done
W/PMS     (  970): mWirelessDisplayManager is still null
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  970):  packet count Tx=371 Rx=357
E/WifiTrafficPoller(  970): notifying of data activity 0
,I/ActivityManager(  970): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=7037 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/AlarmManager(  970): ACTION_SCREEN_ON
D/PMS     (  970): releaseWL(3e10b769): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  970):  packet count Tx=371 Rx=357
,E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=349 rxSum=310} preTxRxSum={txSum=349 rxSum=310}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): handleMessage: E msg.what=131167
,E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 5834): SET_SCREEN_ON:On
I/wpa_supplicant( 5834): htc_wext_set_keepalive +
I/wpa_supplicant( 5834): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 5834): getPrivFuncNum +	
I/wpa_supplicant( 5834): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 5834): htc_wext_set_TX_TRACKING - ret = 0
,E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,D/wpa_supplicant( 5834): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 5834): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-46 linkspeed=150
E/WifiConfigStore(  970): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-46 "NG700"WPA_PSK
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131127
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131129
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
,W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 5834): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 5834): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
,D/WIFI_ICON( 1223): WifiActivity: 0,
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/SRS_Proc(  405): ParamSet string: screen_state=on
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  970): handleMessage: E msg.what=155650
D/NetworkPolicy(  970): updateScreenOn: false
D/WifiController(  970): processMsg: DeviceActiveState
V/NetworkPolicy(  970): updateIfacesLocked()
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/XAN-DPS (  970): prepareColorFade done
,D/XAN-DPS (  970): setBrightness to 0
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1e16b8ce,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1303): [EventService]  onDisplayChanged: 0
,W/SensorService(  970): pid=970, uid=1000
W/ResourcesManager( 7037): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1e16b8ce, eanble = 0, strlen(mName) = 67
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@29efbced
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1303): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457049600000 to /data/system/usagestats/0/daily/1457049602364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457136000000 to /data/system/usagestats/0/daily/1457136002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457308800000 to /data/system/usagestats/0/daily/1457308802364,
I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457395200000 to /data/system/usagestats/0/daily/1457395202364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457481600000 to /data/system/usagestats/0/daily/1457481602364
I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/daily/1457568000000 to /data/system/usagestats/0/daily/1457568002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/weekly/1456358400000 to /data/system/usagestats/0/weekly/1456358402364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/weekly/1456963200000 to /data/system/usagestats/0/weekly/1456963202364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/weekly/1457568000000 to /data/system/usagestats/0/weekly/1457568002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1443743993899 to /data/system/usagestats/0/monthly/1443743996263
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1443744000000 to /data/system/usagestats/0/monthly/1443744002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1446336000000 to /data/system/usagestats/0/monthly/1446336002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1448928000000 to /data/system/usagestats/0/monthly/1448928002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1451520000000 to /data/system/usagestats/0/monthly/1451520002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1454112000000 to /data/system/usagestats/0/monthly/1454112002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/monthly/1456704000000 to /data/system/usagestats/0/monthly/1456704002364
,I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/yearly/1431427267163 to /data/system/usagestats/0/yearly/1431427269527,
I/UsageStatsDatabase(  970): Moving file /data/system/usagestats/0/yearly/1450656000000 to /data/system/usagestats/0/yearly/1450656002364
,I/UsageStatsService(  970): User[0] Rollover scheduled @ 2016-03-11 01:00:00(1457654400000)
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/CalendarProvider2( 7037): Created com.android.providers.calendar.CalendarAlarmManager@2bf88067(com.htc.providers.calendar.HtcCalendarProvider@26983e14),
,D/CalendarProvider2( 7037): wait start:true
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  970): acquireWL(3896c752): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 7037): wait end:false
,D/PMS     (  970): acquireWL(45a0a23): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3896c752): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(45a0a23): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@16dc2248, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1223, uid=10041
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@16dc2248, eanble = 1, strlen(mName) = 57
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@29efbced
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@16dc2248
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/AlarmManager(  970): ACTION_SCREEN_OFF
,I/AlarmManager(  970): [AlarmQueuing] screen off now: 
I/AlarmManager(  970): [AlarmQueuing] data connection: true
I/AlarmManager(  970): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 12
,D/WifiDataStallTracker(  970): stopDataStallAlarm ,
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  970): handleMessage: E msg.what=131167,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
V/SRS_Proc(  405): ParamSet string: screen_state=off
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  970): handleMessage: E msg.what=155651,
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/NetworkPolicy(  970): updateScreenOn: false
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
V/NetworkPolicy(  970): updateIfacesLocked()
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 5834): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 5834): SET_SCREEN_ON:Off
I/wpa_supplicant( 5834): htc_wext_set_keepalive +
I/wpa_supplicant( 5834): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 5834): getPrivFuncNum +	
I/wpa_supplicant( 5834): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5834): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5834): get_ip_address source addr = c0a80166
I/wpa_supplicant( 5834): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 5834): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): handleMessage: X
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2,
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  970): Excessive delay in setPowerMode(): 290ms
D/PMS     (  970): Setting HAL interactive mode to false
D/PMS     (  970): Setting HAL interactive mode to false done
,D/PMS     (  970): Setting HAL auto-suspend mode to true
D/PMS     (  970): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/PMS     (  970): acquireWL(d36069e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/HtcPowerSaver(  970): updateBatteryInfo
I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): releaseWL(d36069e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/InputMethodManagerService(  970): Disable input method client, pid=5686
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
,D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/InputMethodManager( 5686): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{1ac187ba VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3e90adfe
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
D/HABCtrl (  970): TPE algorithm. remove timeout.
D/PMS     (  970): OOBE c monitor 11
,D/PowerUI ( 1223): closing low battery warning: level=100
,D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
D/NfcService( 1511): ScreenObserver: OFF
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NfcService( 1511): applyRouting - 0
,D/PMS     (  970): acquireWL(1239257f): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1511 1027 null,
D/NfcService( 1511): applyRouting -2
D/NfcService( 1511): applyRouting
D/NfcService( 1511): Ignore this applyRouting...
,D/DotMatrix( 1303): [EventService] getTotalRam: 1842 Mb
D/PMS     (  970): releaseWL(1239257f): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/ContactMessageStore( 1489): start background delete task...
,D/ContactMessageStore( 1489): size: 0 , 0
,D/ContactMessageStore( 1489): Background delete complete
,I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  970): acquireWL(2afbd94c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  970): releaseWL(2afbd94c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2638dd95): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1824 10024 WorkSource{10024 com.google.android.gms}
I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): releaseWL(2638dd95): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 7067): MY_DEBUG = false
,D/SmartSyncUtils( 7067): isEpsOn(), nState = 0
,D/PMS     (  970): acquireWL(21b33e38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7067 1000 null
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
,D/PMS     (  970): releaseWL(21b33e38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/RemoteViews( 1223): apply : com.htc.updater 1 19 1 36,
,D/AutoSetting( 1449): service - mHandler: cancel location update
D/AutoSetting( 1449): service -           changes count: 0
,I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
D/SmartDim(  970): Init customizeScreenOffDelayClass error
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,I/ClockController( 1223): stop clock update:screen off
,D/SmartSyncUtils( 7067): isEpsOn(), nState = 0
,D/SmartSyncUtils( 7067): isEpsOn(), nState = 0
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@29efbced
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  970): pid=970, uid=1000
W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@29efbced, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@16dc2248
,W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 2
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@29efbced, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@16dc2248
,W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@32f1d722 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@32f1d722 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  970): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  970): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  970): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  970): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  970): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  970): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  970): 	at com.android.in,ternal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@29efbced
,I/PowerUsageList:PowerUsageHelper( 7067): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/TetherSettings( 6893): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6893): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6893): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6893): Cust_ConnectToPC   : spcsc>false
D/        ( 6893): Cust_ConnectToPC   : IPT>true
D/        ( 6893): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 6893): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 6893): Index of the first 1 = -1
,W/ContextImpl( 6893): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=7101 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,W/ContextImpl( 6893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:BatterySipperExt( 7067): gen(), null == sipper.uidObj, userId = 0
,W/Settings( 6893): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6893): hasRemovableStorageSlot: true,
D/SmartNS_Utility( 6893): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6893): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 6893): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 6893): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PowerUsageService( 7067): calcPower(), no data
,D/PowerUsageList:PowerUsageHelper( 7067): MY_DEBUG = false
,D/Process (  970): killProcessQuiet, pid=5971
I/ActivityManager(  970): Killing 5971:com.google.android.music:main/u0a159 (adj 15): empty #17
D/SmartSyncUtils( 7067): getMobilePolicyEnabled, result = true
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/WifiService(  970): New client listening to asynchronous messages
,E/WifiTrafficPoller(  970): ADD_CLIENT: 8
,I/ActivityManager(  970): Recipient 5971
,D/MediaRouterService(  970): Client com.google.android.music (pid 5971): Died!
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 13 num clients 8
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 13 num clients 8,
,D/Process (  970): killProcessQuiet, pid=6276
I/ActivityManager(  970): Killing 6276:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6276
,D/PMS     (  970): releaseWL(31671994): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/CalendarProvider2( 7037): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 7037): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  970): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=7125 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  970): killProcessQuiet, pid=6742
,I/ActivityManager(  970): Killing 6742:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6742
,W/ResourcesManager( 7125): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 7125): onCreate,
,D/ProviderChangeReceiver( 7125): ---------------------------------------------------,
D/ProviderChangeReceiver( 7125): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  970): Killing 6254:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6254
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 7125): start to updateAlertNotification!
,I/ActivityManager(  970): Recipient 6254,
,D/HtcAlertService( 7125): No fired or scheduled alerts
,D/HtcAlertUtils( 7125): -- cancelReminderNotification --
,D/HtcAlertUtils( 7125): broadcastExistReminder!
,D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1605181724] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1605181724] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  970): handleMessage: X
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1216] from screen [on:0 period:1605182941] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1605182944] gl hn u24 rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 3,
,D/PMS     (  970): acquireWL(47a05e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10072}
,V/AlarmManager(  970): sending alarm PendingIntent{8182a4d: PendingIntentRecord{13bba902 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457599100593, Int=0
D/PMS     (  970): releaseWL(47a05e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 6915): [697] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 6915): [1] 5.onFinished: Installation state replication succeeded.,
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165
E/WifiStateMachine(  970): processMsg: ConnectedState,
E/WifiStateMachine(  970):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  970): handleMessage: X
,I/ActivityManager(  970): Killing 5074:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5074
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5074
,D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1489): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  970): acquireWL(df1c213): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
,V/AlarmManager(  970): sending alarm PendingIntent{6c39c50: PendingIntentRecord{30ca1e49 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=130252, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{10bf534e: PendingIntentRecord{292c6c6f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141948, Int=0
,D/PMS     (  970): acquireWL(1dce2d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2c8d5605): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10176 com.google.android.youtube},
,I/ActivityManager(  970): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7148 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PMS     (  970): releaseWL(1dce2d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(df1c213): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  970): acquireWL(1541565a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(328ea568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/AutoSetting( 1449): service - handleMessage() stop self,
,D/AutoSetting( 1449): service - onDestroy() END
D/AutoSetting( 1449): service - handleMessage() quit looper
,D/PMS     (  970): releaseWL(1541565a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1913): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7148): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7148): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/JNIHelp ( 7148): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/art     ( 1913): Explicit concurrent mark sweep GC freed 25409(1447KB) AllocSpace objects, 3(252KB) LOS objects, 45% free, 4MB/8MB, paused 1.236ms total 94.121ms,
,W/System  ( 7148): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7148): Installed default security provider GmsCore_OpenSSL
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,E/Uploader( 1913): ,	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/art     ( 7148): Suspending all threads took: 9.126ms,
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, success
,E/cutils-trace( 7182): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7182): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2001819053.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads2001819053.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7182): dex2oat: override thread count:4
,E/YouTube MDX( 7148): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7148): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,I/dex2oat ( 7182): dex2oat took 145.396ms (threads: 4)
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,D/VoldConnector(  970): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 7148): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  970): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 7148): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  970): SND -> {39 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
W/ContextImpl( 7148): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/InstanceID/Rpc( 7148): Found 10024
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState what:131326 1 0,
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 1 0
E/WifiStateMachine(  970): handleMessage: X
,D/VoldConnector(  970): SND -> {40 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 7148): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/PMS     (  970): acquireWL(564f7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(564f7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(2c8d5605): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube},
,D/PMS     (  970): acquireWL(1851b20c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(1851b20c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Process (  970): killProcessQuiet, pid=6645
,I/ActivityManager(  970): Killing 6645:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  970): Recipient 6645
,I/art     (  970): Explicit concurrent mark sweep GC freed 56697(3MB) AllocSpace objects, 15(932KB) LOS objects, 33% free, 18MB/28MB, paused 1.850ms total 214.643ms
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided
,W/Uploader( 1913):  no longer exists, so no auth token.
,W/Uploader( 1913): No account for auth token provided,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78),
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided,
,W/Uploader( 1913): No account for auth token provided,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477),
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78),
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1913): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1913): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1913): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1913): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA
,D/PMS     (  970): acquireWL(e7af31f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
W/Uploader( 1913): No account for auth token provided
,W/Uploader( 1913): No account for auth token provided,
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/PMS     (  970): releaseWL(328ea568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(fe5a23b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(fe5a23b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(30d63d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(30d63d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
,D/PMS     (  970): acquireWL(1bf91eb1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null,
D/PMS     (  970): releaseWL(e7af31f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  970): releaseWL(1bf91eb1): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  970): acquireWL(3e522f96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{17c8c61d: PendingIntentRecord{24476092 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158129, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{37822717: PendingIntentRecord{1d1dd704 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457599144174, Int=0
D/PMS     (  970): acquireWL(e4ff4ed): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/WeatherUtility( 1223): Weather sync is On
,D/PMS     (  970): releaseWL(e4ff4ed): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
D/PMS     (  970): releaseWL(3e522f96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  970): acquireWL(10f9af22): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(10f9af22): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): runPSCheck
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1489): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(23f81db3): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{15235f70: PendingIntentRecord{7c3f2e9 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=193232, Int=0
,D/PMS     (  970): releaseWL(23f81db3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1449): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@20e4b91f
,I/ActivityManager(  970): Killing 6777:com.google.android.configupdater/u0a98 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=6777
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6777
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  970): acquireWL(ba79b6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(ba79b6e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 5686): Reconnected to the test server,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): TAP version 13,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 1. multiplex can send data,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 1 String should be length:200,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 2. enqueue and run in order,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 2 firstPromise setTimeout,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 3 firstPromise result,
,I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 4 firstPromise testValue
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 5 secondPromise setTimeout,
,I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 6 secondPromise result
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 7 secondPromise testValue
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 8 thirdPromise in promise
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 9 thirdPromise result
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 10 thirdPromise testValue
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 3. enqueueAtTop and run backwards,
I/jxcore-log( 5686): 
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 11 thirdPromise - first to run,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 12 thirdPromise - in resolve,
,I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 13 secondPromise - second to run
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 14 secondPromise - in catch
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 15 firstPromise - third to run,
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 16 firstPromise - in then
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 17 testing promises
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 4. mix enqueue and enqueueAtTop,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 18 fourth,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 19 fourth,
,I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 20 second
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 21 secondPromise - in then
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 22 first,
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 23 firstPromise - in catch
I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 24 third
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 25 thirdPromise - in then,
,I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 26 testingPromises
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 5. queues handled independently,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 27 all short operations completed before the long resolves,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 6. basic
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 28 sane
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 7. another
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 29 sane
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 8. #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 30 specific error should be returned
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 31 error should be null
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 32 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # 9. #startUpdateAdvertisingAndListening should fail if start not called
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 33 specific error should be returned
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 34 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 35 error should be null
I/jxcore-log( 5686): ,
I/jxcore-log( 5686): # 10. should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 36 error should be null
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 37 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 38 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 39 error should be null
,I/jxcore-log( 5686): 
I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 40 error should be null
I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 41 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 11. should be able to call #startListeningForAdvertisements many times,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 42 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 43 error should be null,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 44 error should be null
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 45 error should be null
I/jxcore-log( 5686): 
I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 46 error should be null
,I/jxcore-log( 5686): 
I/jxcore-log( 5686): ok 47 error should be null,
I/jxcore-log( 5686): 
I/jxcore-log( 5686): # 12. should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 48 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 49 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 50 error should be null
I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 51 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 52 error should be null
I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 53 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 13. should be able to call #stopAdvertisingAndListening many times,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 54 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 55 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 56 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 57 error should be null,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 58 error should be null
I/jxcore-log( 5686): ,
I/jxcore-log( 5686): ok 59 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 14. #start should fail if called twice in a row
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 60 first call should succeed
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 61 first call should succeed
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 62 specific error should be returned
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 63 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 64 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 15. does not emit duplicate discoveryAdvertisingStateUpdate
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 65 called only once
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 66 discovery state matches
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 67 advertising state matches
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 68 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 69 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 16. does not send duplicate availability changes
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 70 should be called once
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 71 should not have been called more than once
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 72 error should be null
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 73 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 17. can get the network status
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 74 network status should have certain non-empty properties
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 75 error should be null
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 76 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # 18. wifi peer is marked unavailable if announcements stop
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 77 host address should match
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 78 port should match
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 79 host address should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 80 port should should be null
,I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): ok 81 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): ok 82 error should be null
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686): # 19. Can call start/stopListeningForAdvertisements,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): ,
,I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: -1, start advertisements: false
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true,
,I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
,I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): initialize: My bluetooth address is 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5686): bind: Binding a new listener
,V/io.jxcore.node.ConnectivityInfo( 5686): setIsWifiEnabled: true
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 5686): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 5686): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startAdvertiser: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): onIsServerStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): setState: NOT_STARTED -> RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections: OK
,I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [ADVERTISING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onAdvertiserFailedToStart: 1
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
,W/BluetoothAdapter( 5686): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
,I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-btm  ( 5769): BTM_AllocateSCN
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 5769):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Waiting for incoming connections...
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 83 Can call startListeningForAdvertisements without error
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): ,
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started',
,I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping only listening for advertisements
V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,I/jxcore-log( 5686): ok 84 Can call stopListeningForAdvertisements without error
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping only listening for advertisements,
,V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,I/jxcore-log( 5686): ok 85 Should be able to call stopListeningForAdvertisments in teardown
I/jxcore-log( 5686): ,
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping all activities and killing all connections
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): stopListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5686): release: No more listeners, de-initializing...
I/bt-btif ( 5769): BTA_JvDeleteRecord
I/bt-btif ( 5769): BTA_JvRfcommStopServer
,D/bt-btm  ( 5769): BTM_FreeSCN 
D/bt-sdp  ( 5769): SDP_DeleteRecord ok, num_records:15
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Bluetooth server socket closed
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): onServerStopped: Was explicitly stopped: true
D/io.jxcore.node.HandshakeHelper( 5686): shutdown
D/io.jxcore.node.ConnectivityInfo( 5686): stopMonitoring: Stopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): onIsServerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): setState: RUNNING -> NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5686): onConnectionManagerStateChanged: NOT_STARTED
D/io.jxcore.node.StartStopOperationHandler( 5686): checkCurrentOperationStatus: Operation successfully executed
I/jxcore-log( 5686): ok 86 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 5686): 
I/bt-btm  ( 5769): BTM_SEC_CLR[19]: id 61
,I/jxcore-log( 5686): # 20. Calling startListeningForAdvertisements twice is NOT an error
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: -1, start advertisements: false
,D/io.jxcore.node.HandshakeHelper( 5686): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
,I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true,
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener,
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): initialize: My bluetooth address is 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5686): bind: Binding a new listener
V/io.jxcore.node.ConnectivityInfo( 5686): setIsWifiEnabled: true
I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startAdvertiser: Starting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): onIsServerStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): setState: NOT_STARTED -> RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections: OK
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [ADVERTISING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onAdvertiserFailedToStart: 1
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
W/BluetoothAdapter( 5686): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
I/bt-btif ( 5769): BTA_JvCreateRecordByUser
D/bt-btm  ( 5769): BTM_AllocateSCN
,D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 5769):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Waiting for incoming connections...
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 3
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 87 Can call startListeningForAdvertisements without error
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ---,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       false,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: -1, start advertisements: false
V/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: Already started,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: true
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startAdvertiser: Starting...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections: Already running, call stopListeningForIncomingConnections() first in order to restart
,I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4,
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [ADVERTISING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onAdvertiserFailedToStart: 1
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
I/jxcore-log( 5686): 
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 88 Can call startListeningForAdvertisements twice without error
,I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): ,
I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping only listening for advertisements,
,V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,I/jxcore-log( 5686): ok 89 Should be able to call stopListeningForAdvertisments in teardown,
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping all activities and killing all connections
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): stopListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5686): release: No more listeners, de-initializing...
I/bt-btif ( 5769): BTA_JvDeleteRecord
I/bt-btif ( 5769): BTA_JvRfcommStopServer
D/bt-btm  ( 5769): BTM_FreeSCN 
D/bt-sdp  ( 5769): SDP_DeleteRecord ok, num_records:15
I/bt-btm  ( 5769): BTM_SEC_CLR[19]: id 61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): release: No more listeners, de-initializing...
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Bluetooth server socket closed
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): onServerStopped: Was explicitly stopped: true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): onIsServerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): setState: RUNNING -> NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5686): onConnectionManagerStateChanged: NOT_STARTED
D/io.jxcore.node.HandshakeHelper( 5686): shutdown
D/io.jxcore.node.StartStopOperationHandler( 5686): checkCurrentOperationStatus: Operation successfully executed
D/io.jxcore.node.ConnectivityInfo( 5686): stopMonitoring: Stopped
,I/jxcore-log( 5686): ok 90 Should be able to call stopAdvertisingAndListening in teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 21. Can call start/stopUpdateAdvertisingAndListening
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: 4242, start advertisements: true
,D/io.jxcore.node.HandshakeHelper( 5686): reinitiate,
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): initialize: My bluetooth address is 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5686): bind: Binding a new listener
V/io.jxcore.node.ConnectivityInfo( 5686): setIsWifiEnabled: true
I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
,I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 91 Can call startUpdateAdvertisingAndListening without error,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping all activities and killing all connections,
V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
D/io.jxcore.node.HandshakeHelper( 5686): shutdown
D/io.jxcore.node.ConnectivityInfo( 5686): stopMonitoring: Stopped
,I/jxcore-log( 5686): ok 92 Can call stopAdvertisingAndListening without error,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping only listening for advertisements,
,V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,I/jxcore-log( 5686): ok 93 Should be able to call stopListeningForAdvertisments in teardown,
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping all activities and killing all connections
V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,I/jxcore-log( 5686): ok 94 Should be able to call stopAdvertisingAndListening in teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 22. Calling startUpdateAdvertisingAndListening twice is NOT an error,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: 4242, start advertisements: true,
D/io.jxcore.node.HandshakeHelper( 5686): reinitiate,
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,D/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: false
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 95 Can call startUpdateAdvertisingAndListening without error,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ---,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: 4243, start advertisements: true
V/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: Already started
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: false
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 96 Can call startUpdateAdvertisingAndListening twice without error,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       false,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # setup,
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping only listening for advertisements,
V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,I/jxcore-log( 5686): ok 97 Should be able to call stopListeningForAdvertisments in teardown,
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): stop: Stopping all activities and killing all connections
V/io.jxcore.node.StartStopOperationHandler( 5686): executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
D/io.jxcore.node.HandshakeHelper( 5686): shutdown
,D/io.jxcore.node.ConnectivityInfo( 5686): stopMonitoring: Stopped
,I/jxcore-log( 5686): ok 98 Should be able to call stopAdvertisingAndListening in teardown,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # 23. peerAvailabilityChange is called,
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): # teardown,
I/jxcore-log( 5686): 
,I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: 4242, start advertisements: true,
D/io.jxcore.node.HandshakeHelper( 5686): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 5686): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5686):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5686):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5686):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5686): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: false
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
,D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
I/jxcore-log( 5686): 
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 99 Can call startUpdateAdvertisingAndListeningwithout error,
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk,
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
I/io.jxcore.node.ConnectionHelper( 5686): start: Port number: 4242, start advertisements: false
,V/io.jxcore.node.ConnectivityInfo( 5686): startMonitoring: Already started
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: Discovery mode: BLE, start discovery: true, start advertiser: true
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startScanner: Starting...
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): onScanFailed: Feature is not supported, error code is 4
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: true, is advertising: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5686): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsScannerStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): startAdvertiser: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5686): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/BluetoothAdapter( 5686): 939196857: getState(). Returning 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [SCANNING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): start: OK
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onScannerFailed: 4
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5686): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5686): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): onIsServerStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): setState: NOT_STARTED -> RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5686): startListeningForIncomingConnections: OK
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5686): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): updateState: State changed from [ADVERTISING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5686): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5686): onAdvertiserFailedToStart: 1
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
I/io.jxcore.node.ConnectionHelper( 5686): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5686): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 5686): start: OK
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
I/jxcore-log( 5686): 
,D/BluetoothManagerService(  970): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5686): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
,I/bt-btif ( 5769): BTA_JvCreateRecordByUser
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 5686): 
D/bt-btm  ( 5769): BTM_AllocateSCN
D/bt-sdp  ( 5769): SDP_CreateRecord ok, num_records:16
I/bt-btif ( 5769): BTA_JvRfcommStartServer
I/bt-btm  ( 5769): BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
I/bt-btm  ( 5769):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5686): Waiting for incoming connections...
I/jxcore-log( 5686): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 5686): 
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/io.jxcore.node.StartStopOperationHandler( 5686): Operation timeout, state error: Discovery manager not started,
,I/jxcore-log( 5686): not ok 100 Can call startListeningForAdvertisements without error,
I/jxcore-log( 5686): ,
,I/jxcore-log( 5686):   ---
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     operator: notOk
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     expected: |-
I/jxcore-log( 5686): 
I/jxcore-log( 5686):       false
I/jxcore-log( 5686): 
I/jxcore-log( 5686):     actual: |-
I/jxcore-log( 5686): 
,I/jxcore-log( 5686):       'Operation timeout, state error: Discovery manager not started'
I/jxcore-log( 5686): 
I/jxcore-log( 5686):   ...
I/jxcore-log( 5686): 
,D/wpa_supplicant( 5834): wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 11 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 13 BSSID 00:1f:27:54:70:c4 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c3 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 14 BSSID 00:1e:4a:8f:e3:62 SSID '\x00' due to wpa_bss_flush_by_age
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
,D/wpa_supplicant( 5834): wlan0: BSS: Remove id 15 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 16 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:6b]
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 5 BSSID 10:d3:8a:bb:6a:65 SSID 'Komorka Samsung' due to wpa_bss_flush_by_age
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:6b
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 17 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
,D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6f]
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e4 SSID '\x00' due to wpa_bss_flush_by_age
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6f
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 18 BSSID 00:1f:27:54:70:c2 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:70:c4]
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:70:c5 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:70:c4
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 8 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c3]
,E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c3
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 9 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 5834): wlan0: BSS: Remove id 10 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:62]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:1e:4a:8f:e3:62
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:e3:64]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:1e:4a:8f:e3:64
,D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:e3:60]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:e3:60
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 10:d3:8a:bb:6a:65]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 10:d3:8a:bb:6a:65
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 00:16:a6:1f:06:5c]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 17 00:16:a6:1f:06:5c
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e4]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e4
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 18 00:1f:27:54:70:c2]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 18 00:1f:27:54:70:c2,
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:70:c5]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:70:c5
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:63]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:63
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:22:0d:46:1c:a3]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:22:0d:46:1c:a3
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e3]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e3
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(1e9ffefc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{17c8c61d: PendingIntentRecord{24476092 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218130, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{365743da: PendingIntentRecord{e70800b com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457599319999, Int=0
D/PMS     (  970): releaseWL(1e9ffefc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  970): acquireWL(6c0ee8): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{3ff5c3a6: PendingIntentRecord{15a511e7 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=388987, Int=0
D/PMS     (  970): acquireWL(9fd3901): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 970 1000 null
D/PMS     (  970): acquireWL(2673194): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/PMS     (  970): releaseWL(6c0ee8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  970): releaseWL(9fd3901): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,D/PMS     (  970): releaseWL(2673194): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 4
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6915): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6915): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6915): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6915): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6915): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6915): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6915): 	at android.os.Binder.execTransact(Binder.java:454)
,I/art     ( 1913): Background sticky concurrent mark sweep GC freed 45024(2MB) AllocSpace objects, 16(1112KB) LOS objects, 41% free, 5MB/8MB, paused 5.710ms total 69.202ms
,W/System  ( 6915): Ignoring header User-Agent because its value was null.,
D/libc    ( 6915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 6915): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 6915): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6915): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6915): [NET] android_getaddrinfo_proxy+
D/libc    ( 6915): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6915): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(310c6256): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(310c6256): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): << updateStatus
,D/WifiController(  970): handleMessage: X
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success,
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+,
D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0,
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 7148): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 7148): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7148): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 7148): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,D/libc    ( 7148): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 7148): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 7148): [NET] android_getaddrinfofornet-, err=8
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  451): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1489): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1489): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1489): sku_id=118
D/ContactMessageStore( 1489): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1489): start background delete task...
,D/ContactMessageStore( 1489): size: 0 , 0,
D/ContactMessageStore( 1489): Background delete complete
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): acquireWL(cc042d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): releaseWL(cc042d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): handleMessage: E msg.what=155652
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DefaultState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(b8427c4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{17c8c61d: PendingIntentRecord{24476092 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398129, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{30fad6ad: PendingIntentRecord{3f044de2 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=981496, Int=0
I/bt-btm  ( 5769): Received oneshot timer event complete
I/bt-btm  ( 5769): btm_ble_timeout
D/PMS     (  970): acquireWL(35c3573): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5769 1002 null
I/bt-btm  ( 5769): btm_gen_resolvable_private_addr
,D/bt-btm  ( 5769): btm_ble_rand_enc_complete
I/bt-btm  ( 5769): btm_gen_resolve_paddr_low
D/bt-smp  ( 5769): smp_encrypt_data
,W/bt-smp  ( 5769): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5769): Plain text(LSB ~ MSB) = 36 a8 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5769): Encrypted text(LSB ~ MSB) = f7 b0 19 a0 e0 ea ad 6c b8 42 bc 33 9a de 12 0e 
I/bt-btm  ( 5769): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5769): Stopping oneshot timer
D/bt-btm  ( 5769): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(b8427c4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(35c3573): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  970): acquireWL(107dfc30): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
V/AlarmManager(  970): sending alarm PendingIntent{259b30a9: PendingIntentRecord{179d662e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=992652, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{2c87f57e: PendingIntentRecord{241adf android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805384, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{38bab5cf: PendingIntentRecord{a651242 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457599940047, Int=0
,D/PMS     (  970): acquireWL(37feab5c): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(37feab5c): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): releaseWL(107dfc30): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 7067): MY_DEBUG = false
,D/PowerUsageService( 7067): repeat time = 1457600874562
,D/PMS     (  970): acquireWL(269db73a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(2fd6dfeb): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,I/GCM     ( 4218): Message from null null
,E/GCM     ( 4218): Dropping message from null
,D/PMS     (  970): releaseWL(2fd6dfeb): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1913): Message class com.google.f.a.a.i,
,D/PMS     (  970): releaseWL(269db73a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 7067): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 7067): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 7067): calcPower(), no data,
,D/PMS     (  970): acquireWL(31792148): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{17c8c61d: PendingIntentRecord{24476092 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998129, Int=0,
,V/AlarmManager(  970): sending alarm PendingIntent{3e674be1: PendingIntentRecord{1c200d06 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457599993965, Int=0
D/SmartSyncUtils( 7067): isEpsOn(), nState = 0
,D/PMS     (  970): acquireWL(16418fc7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7067 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 7067): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 7067): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
D/PMS     (  970): releaseWL(31792148): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 7067): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 7067): SettingOnTime = 1457676000000, randomSettingOnTime = 1457675842000
,D/SmartSyncScreenOnOffTimeReceiver( 7067): SettingOffTime = 1457654400000, randomSettingOffTime = 1457659694000
,D/WeatherUtility( 1223): Weather sync is On
D/SmartSyncScreenOnOffTimeReceiver( 7067): bDayMode = false
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 7067): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 7067): bNightModeTurnOffOnce = false
,D/PMS     (  970): releaseWL(16418fc7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): acquireWL(2ea309f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  970): releaseWL(2ea309f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 5769): Disconnected process message: 10, size: 0
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
