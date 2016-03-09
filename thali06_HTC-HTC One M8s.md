#### Test 6012434764ab483_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 4188): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/PeopleContactsSync( 4188): CP2 sync disabled
--------- beginning of system
D/PMS     (  985): releaseWL(29e2ce2c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/Vision  ( 4188): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 4188): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4188): No vision deps
I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4188, uid=10024, userID:0
V/ConfigFetchTask( 4188): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/GoogleURLConnFactory( 4188): Using platform SSLCertificateSocketFactory
I/ActivityManager(  985): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5683 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
D/libc    ( 4188): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4188): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4188): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4188): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4188): [NET] android_getaddrinfo_proxy+
D/libc    ( 4188): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4188): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4188): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 4188): fetch service done; releasing wakelock
D/PMS     (  985): releaseWL(1c0161df): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest}
I/ConfigFetchService( 4188): stopping self
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
W/BaseAppContext( 4188): Using Auth Proxy for data requests.
I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@1cbb7073 +
I/Prism.WidgetManager( 1590): onLoadItems() +
E/cutils-trace( 5709): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5709): ====startRecUseTime====
D/htc.customization.log.level( 5709):  is 
W/CustomizationLogLevel( 5709): Level value is invalid, use default level 2
D/CustomizationManager( 5709):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5709): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5709): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5709): Parsing tag category name = system
I/CustomizationCIDLoader( 5709): Parsing tag category name = application
I/CustomizationCIDLoader( 5709): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5709): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5709): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5709): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5709): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5709): add string-array item, value = 42507
I/CustomizationCIDLoader( 5709): add string-array item, value = 21902
I/CustomizationCIDLoader( 5709): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5709): add string-array item, value = 23420
I/CustomizationCIDLoader( 5709): add string-array item, value = 22299
I/CustomizationCIDLoader( 5709): add string-array item, value = 24002
I/CustomizationCIDLoader( 5709): add string-array item, value = 23210
I/CustomizationCIDLoader( 5709): add string-array item, value = 23205
I/CustomizationCIDLoader( 5709): add string-array item, value = 23806
I/CustomizationCIDLoader( 5709): add string-array item, value = 23430
I/CustomizationCIDLoader( 5709): add string-array item, value = 23408
I/CustomizationCIDLoader( 5709): add string-array item, value = 27205
I/CustomizationCIDLoader( 5709): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5709): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5709):  Read CID file spent 0.091 (s)
D/CustomizationManager( 5709):  All configurations done spent 0.092 (s)
D/AutoSetting( 1504): service - handleMessage() stop self
I/ActivityManager(  985): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5709 on display 0
D/PMS     (  985): acquireHCC(2c0fadd7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 985 1000 null
D/PMS     (  985): acquireHCC(14eeb6c4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 985 1000 null
W/asset   (  985): Copying FileAsset 0x55baaa4830 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  985): acquireWL(3fb75073): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 985 1000 null
D/AutoSetting( 1504): service - handleMessage() quit looper
I/FeedHostManager( 1590): [onPause]
I/FeedProviderManager( 1590): onPause
D/AutoSetting( 1504): service - onDestroy() END
I/FeedHostManager( 1590): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1eae810c
I/SocialFeedProvider( 1590): +onPause
I/SocialFeedProvider( 1590): -onPause
I/AnimationUtil(  985): isHTCRecent(ThaliTest/Recent screens.)/9
W/HtcSystemUPManager(  985): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  985): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5734 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/GAv4    ( 5683): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5683):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5683):   adb logcat -s GAv4
W/GAv4    ( 5683): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  985): Killing 3629:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  985): killProcessQuiet, pid=3629
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/GAv4    ( 5683): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Prism.WidgetManager( 1590): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1590): onLoadItems() -
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@1cbb7073 -
W/asset   ( 5734): Copying FileAsset 0xac6fca80 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  985): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  985): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  985): hiding MENU key
W/GAv4    ( 5683): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/TrimMemoryManager( 1590): [trimMemory] 20
W/AnalyticsTrackerProxyImpl( 5683): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
D/ChimeraCfgMgr( 4188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4188): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  985): Recipient 3629
,D/PhoneApp( 1533): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1533): -- N1 =0
,D/PhoneApp( 1533): -- N2 =0
,D/PhoneApp( 1533): -- N3 =0
,D/VoldConnector(  985): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5683): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,D/PMS     (  985): acquireWL(15525a92): PARTIAL_WAKE_LOCK  AsyncService 0x1 5500 10167 null
,D/PMS     (  985): releaseWL(15525a92): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  985): acquireWL(11831060): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5500 10167 null
,W/ResourcesManager( 5683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  985): releaseWL(11831060): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/WebViewFactory( 5734): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/UpdateIcingCorporaServi( 5354): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
V/JNIHelp ( 5683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/LibraryLoader( 5734): Time to load native libraries: 10 ms (timestamps 5693-5703)
,I/LibraryLoader( 5734): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5734): Binding Chromium to main looper Looper (main, tid 1) {1ba3f2f4}
,I/LibraryLoader( 5734): Expected native library version number "",actual native library version number ""
W/asset   ( 5354): Copying FileAsset 0x55ba1b1350 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/chromium( 5734): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/UpdateIcingCorporaServi( 5354): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,W/System  ( 5683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ActivityManager(  985): Killing 4996:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
I/ProviderInstaller( 5683): Installed default security provider GmsCore_OpenSSL
D/Process (  985): killProcessQuiet, pid=4996
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/BrowserStartupController( 5734): Initializing chromium process, singleProcess=true
,W/art     ( 5734): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5734): ApplicationContext is null in ApplicationStatus,
,I/ActivityManager(  985): Recipient 4996
,W/chromium( 5734): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 5734): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5734): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5734): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5734): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5734): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5734): Local Branch: 
I/Adreno-EGL( 5734): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006,
I/Adreno-EGL( 5734): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5734):                  d74aa161a12b9c6fc6332151
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManagerService(  985): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  985): java.lang.Throwable: stack dump
D/BluetoothManagerService(  985): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@377e0453:true
W/System.err(  985): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  985): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  985): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  985): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 5734): 193415776: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5734): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5734): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 5734): CordovaWebView is running on device made by: HTC
,W/art     ( 5734): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 5734): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5734): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 5734): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/HtcModeClient( 3122): handler message = 4011
E/HtcModeClient( 3122): Check connection and retry 7 times.
,I/InputMethodManager( 5734): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@45450bc, mServedView=org.apache.cordova.engine.SystemWebView{35e7d845 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@21fa4b9a
,I/InputMethodManagerService(  985): Disable input method client, pid=1590
D/StatusBarManagerService(  985): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  985): Enable input method client, pid=5734
,I/PhoneStatusBar( 1236): setImeWindowStatus(false,false)
,D/PMS     (  985): releaseWL(3fb75073): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  985): Displayed com.test.thalitest/.MainActivity: +1s63ms
,W/XT9_C   ( 1391): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1391): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5734): Cannot call determinedVisibility() - never saw a connection for the pid: 5734,
,D/JsMessageQueue( 5734): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5734): JniHelper::setJavaVM(0xab5908f8), pthread_self() = -1400145928
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5734): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c99879f added. We now have 1 listener(s)
D/BluetoothManagerService(  985): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5734): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5734): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1698febb added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5734): addListener: New listener added - the number of listeners is now 1
D/WifiService(  985): New client listening to asynchronous messages
E/WifiTrafficPoller(  985): ADD_CLIENT: 7
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5734): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5734): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5734): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5734): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5734): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/ActivityManager(  985): Killing 5069:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  985): killProcessQuiet, pid=5069
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/chromium( 5734): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  985): Recipient 5069
D/Process (  985): killProcessQuiet, pid=5328
I/ActivityManager(  985): Killing 5328:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  985): Recipient 5328
,D/PMS     (  985): releaseHCC(2c0fadd7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  985): releaseHCC(14eeb6c4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5734): Initializing JXcore engine
W/jxcore-log( 5734): JXcore engine is ready
,W/jxcore-log( 5734): Starting JXcore engine,
,W/jxcore-log( 5734): Platform android,
W/jxcore-log( 5734): 
W/jxcore-log( 5734): Process ARCH arm
W/jxcore-log( 5734): 
,I/jxcore-log( 5734): JXcore Cordova bridge is ready!,
I/jxcore-log( 5734): 
,W/jxcore-log( 5734): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5734): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ActivityManager(  985): Waited long enough for: ServiceRecord{3fbac2cd u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  985): Waited long enough for: ServiceRecord{bffd0b u0 com.htc.musicenhancer/.EnhancerService},
,W/MediaManager( 4891): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  985): killProcessQuiet, pid=5543
I/ActivityManager(  985): Killing 5543:com.htc.task/u0a69 (adj 15): empty #17
,D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5543
,I/ConfigService( 1907): onDestroy,
,D/Process (  985): killProcessQuiet, pid=5228,
I/ActivityManager(  985): Killing 5228:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5228
,I/HtcModeClient( 3122): handler message = 4011,
E/HtcModeClient( 3122): Check connection and retry 8 times.
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5734): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 5734): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 5734): BLE multiple advertisement supported
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): My device name is: HTC-HTC One M8s
I/jxcore-log( 5734): 
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 3122): handler message = 4011,
E/HtcModeClient( 3122): Check connection and retry 9 times.
,D/PMS     (  985): acquireWL(2f1ac784): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{1000}
V/AlarmManager(  985): sending alarm PendingIntent{b495b6d: PendingIntentRecord{b6553a2 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=86252, Int=0
,D/PMS     (  985): releaseWL(2f1ac784): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native,
I/jxcore-log( 5734): 
,I/io.jxcore.node.ConnectivityInfo( 5734): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 5734):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5734):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5734):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 5734):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5734):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 5734):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 5734):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 5734):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5734): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 5734): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5734): 
,D/ContactMessageStore( 1533): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1533): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 3122): handler message = 4011,
E/HtcModeClient( 3122): Check connection and retry 10 times.,
,D/PMS     (  985): acquireWL(253ed7f0): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{10072}
V/AlarmManager(  985): sending alarm PendingIntent{352d4169: PendingIntentRecord{2e6907ee com.android.vending startService}}, i=null, t=0, cnt=1, w=1457487507265, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{1337148f: PendingIntentRecord{ab1613b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=91508, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{2c51831c: PendingIntentRecord{384f8b25 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=86687, Int=0
,D/PMS     (  985): acquireWL(39e1b4fa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1907 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  410): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  985): releaseWL(39e1b4fa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): releaseWL(253ed7f0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  985): [NET] android_getaddrinfofornet-, err=8
D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  985): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  985): [NET] android_getaddrinfo_proxy+
D/libc    (  985): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    (  985): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  985): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5817 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  985): Explicit concurrent mark sweep GC freed 23867(1285KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.491ms total 142.971ms
,W/ResourcesManager( 5817): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/Finsky  ( 5431): [547] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5431): [1] 5.onFinished: Installation state replication succeeded.
,I/Babel_SMS( 5817): MmsConfig: mnc/mcc: 0/0,
,I/Babel_SMS( 5817): MmsConfig.loadMmsSettings
,I/ActivityManager(  985): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5847 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5817, uid=10112, userID:0
,W/Settings( 5817): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/HtcWrapAdjustableCursorFactory( 5847): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,I/Babel_Crash( 5817): startup - clean
,D/MessageFrequencyProvider( 5847): onCreate
,V/GetPrviateResource( 5847): GetPrviateResource
,V/GetPrviateResource( 5847): GetPrviateResource
,D/MmsCustomizationProvider( 5847): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/Babel   ( 5817): deleted: false for 0
,D/MessageCustFlag( 5847): sense_version=6.0
,D/BTAccessoryUtil( 5847): createReceiver
,D/BTAccessoryUtil( 5847): registerReceiver return intent = null
D/MessageCustFlag( 5847): sku_id=118,
,D/MmsCustomizationProvider( 5847): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/HtcBuildUtils( 5847): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5847): Cannot find qct_8960_interface, use default value instead
,I/Babel_SMS( 5817): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 5817): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5817): canonicalizeMccMnc: invalid mccmnc 
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5817, uid=10112, userID:0
I/Babel_SMS( 5817): MmsConfig.loadFromResources
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5817, uid=10112, userID:0
,E/Babel_SMS( 5817): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5817): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5817, uid=10112, userID:0
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5817, uid=10112, userID:0
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5817, uid=10112, userID:0
,W/VideoCapabilities( 5817): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5817): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5817): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5817): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5817): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5817): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5817): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 5817): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 5817): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5817): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5817): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5817): Unrecognized profile 2130706433 for video/avc,
,D/Process (  985): killProcessQuiet, pid=4926,
I/ActivityManager(  985): Killing 4926:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 4926,
,D/Process (  985): killProcessQuiet, pid=5568
I/ActivityManager(  985): Killing 5568:com.nero.android.htc.sync/u0a5 (adj 15): empty #18
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaRouterService(  985): Client com.google.android.music (pid 4926): Died!
,I/ActivityManager(  985): Recipient 5568
,D/WifiService(  985): Client connection lost with reason: 4
,I/vclib   ( 5817): onServiceConnected,
W/Babel   ( 5817): Attempted to change video mute state without an active call.,
,I/art     ( 1907): Explicit concurrent mark sweep GC freed 15244(838KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 886us total 36.666ms,
,D/Messaging( 5847): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5847): networkCode: 
D/MessageCustFlag( 5847): sku_id=118
D/MmsConfig( 5847): SIE smsPri: null
D/MmsConfig( 5847): networkCode: 
,D/MmsConfig( 5847): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 5847): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5847): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5847): 
D/MmsAsyncWorkHandler( 5847): HM tk = 20001
,D/ReportIndicatorCache( 5847): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5847): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1ba3f2f4
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1533): sku_id=118
D/DraftCache( 5847): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5847): [DraftCache/1] refresh
,D/DraftCache( 5847): [DraftCache/142] rebuildCache
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1533):  slotId = -1000
D/MmsSmsV2Provider( 1533): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,I/Messaging( 5847): mccmnc> 
,D/MmsConfig( 5847): networkCode: 
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1533):  slotId = -1000
D/MmsSmsV2Provider( 1533): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5847): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1533):  slotId = -1000
D/MmsSmsV2Provider( 1533): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5847): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 1533): URI_DRAFT
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,D/DraftCache( 5847): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5847): [DraftCache/142] rebuildCache time: 17
D/MmsAsyncWorkHandler( 5847): 
D/MmsAsyncWorkHandler( 5847): HM tk = 20002
D/MmsSmsV2Provider( 1533):  slotId = -1000
,D/MmsSmsV2Provider( 1533): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1533): sku_id=118
,D/PhoneStorageUtil( 5847): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5847): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5847): createReceiver
D/Messaging( 5847): mNeedToUpdateDate2: false
,D/MessageCustFlag( 5847): sense_version=6.0
D/Jerry   ( 5847): start to preload cursor >>>>>>>
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
,D/AccFlag ( 1533): sku_id=118
D/TelephUtils( 1533): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1533): Update uri=content://mms, match=0
V/MmsProvider( 1533): selection=st=129 AND m_type!=134
D/Messaging( 5847): Reset downloading state: 0
V/MmsSystemEventReceiver( 5847): TransactionService is going to be woken up.
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1533):  slotId = -1000
,V/TransactionService( 5847): 1-Creating TransactionService
,D/Messaging( 5847): ViewCache CreatePreload
D/Messaging( 5847): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 5847): _has_set_default_values_2=true,
,D/MsgPreferenceUtils( 5847): def_index: 0
,V/TransactionService( 5847): onStartCommand: 1
,D/MmsSystemEventReceiver( 5847): unRegisterForConnectionStateChanges
,V/TransactionService( 5847): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5847): Loading previous transactions.
D/MsgPreferenceUtils( 5847): globalIndex = 1
,D/MsgPreferenceUtils( 5847): phone state: true
D/MsgPreferenceUtils( 5847): sd state: false
D/MsgPreferenceUtils( 5847): vIndex = 0
,D/TelephUtils( 1533): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1533): device_type: 1
,D/TransactionService( 5847): Force clearing mTransactionList,
D/TransactionService( 5847): Force set service start id to 1
V/TransactionService( 5847): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5847): unRegisterForConnectionStateChanges
,D/TransactionService( 5847): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5847): Destroying TransactionService
,V/TransactionService( 5847): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5734): ,
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 5734): 
,I/jxcore-log( 5734): Unit Test app is loaded
I/jxcore-log( 5734): 
,I/chromium( 5734): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66),
,I/jxcore-log( 5734): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 5734): 
,I/HtcModeClient( 3122): handler message = 4011
E/HtcModeClient( 3122): Check connection and retry 11 times.
,W/ContextImpl(  985): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3122): handler message = 4011,
E/HtcModeClient( 3122): Check connection and retry 12 times.
,I/HtcModeClient( 3122): handler message = 4011,
,E/HtcModeClient( 3122): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3122): Don't start project servcice,
,D/HtcModeClient( 3122): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3122): connectState: CONNECTION_READY = false,
D/SilentMusic( 3122): call stop
D/HtcModeClient( 3122): close connection
,W/HtcModeClient( 3122): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3122): read the terminate packet, so break
,D/Process (  985): killProcessQuiet, pid=3122
I/ActivityManager(  985): Killing 3122:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 3122
,I/ActivityManager(  985): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5900 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  985): acquireWL(3d5f695f): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{10076}
,V/AlarmManager(  985): sending alarm PendingIntent{1234ffac: PendingIntentRecord{117f7475 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457487526043, Int=60000
D/PMS     (  985): releaseWL(3d5f695f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5900): SMSBackupAgentService started
,D/SMSBackup( 5900): Checking restore status
,D/SMSBackup( 5900): Restore complete,
,D/SMSBackup( 5900): cancelCheckAlarm
,D/SMSBackup( 5900): SMSBackupAgentService completed: completed in 0.0 seconds,
,I/ActivityManager(  985): Killing 5259:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  985): killProcessQuiet, pid=5259,
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  985): Recipient 5259
,I/PMS     (  985): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  985): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@17a144cc
W/SensorService(  985): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  985): disable: get sensor name = Accelerometer Sensor,
,W/SensorService(  985): pid=985, uid=1000
W/PMN     (  985): goingToSleep
W/SensorService(  985): Active sensors: size = 4,
W/SensorService(  985): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  985): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  985): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  985): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  985): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@17a144cc, eanble = 0, strlen(mName) = 91
W/SensorService(  985): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  985): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@73f4eae
W/SensorService(  985): Listener[1] = com.htc.smartdim.sensor_eye@4fae377
W/SensorService(  985): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1236): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  985): mWirelessDisplayManager is null
W/PMS     (  985): mWirelessDisplayManager is still null
D/PMS     (  985): acquireWL(93b3c7b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 985 1000 null
,I/PMS     (  985): Sleeping (uid 1000)...,
D/XAN-DPS (  985): prepareColorFade 1
,W/PMN     (  985): goingToSleep done
,W/HtcSystemUPManager(  985): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  985): releaseWL(93b3c7b): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/Adreno-EGL(  985): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  985): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  985): Build Date: 03/09/15 Mon
I/Adreno-EGL(  985): Local Branch: 
I/Adreno-EGL(  985): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  985): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  985):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  985): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5924 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/AlarmManager(  985): ACTION_SCREEN_ON
I/AlarmManager(  985): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  985): [AlarmQueuing] done recovering
I/AlarmManager(  985): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  985): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  985): handleMessage: E msg.what=131167,
E/WifiStateMachine(  985): processMsg: InitialState
E/WifiStateMachine(  985):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  985): processMsg: DefaultState
E/WifiStateMachine(  985):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  985):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
V/SRS_Proc(  416): ParamSet string: screen_state=on
E/audio_a2dp_hw(  416): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  985): getWifiLinkLayerStats: WIFI is not enbled,
D/WifiStateMachine(  985): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  985): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  985): handleMessage: X
E/WifiStateMachine(  985): handleMessage: E msg.what=131154
,E/WifiStateMachine(  985): processMsg: InitialState
,E/WifiStateMachine(  985):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  985): processMsg: DefaultState
E/WifiStateMachine(  985):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  985): handleMessage: X
,E/WifiStateMachine(  985): handleMessage: E msg.what=131127,
D/NetworkPolicy(  985): updateScreenOn: false,
E/WifiStateMachine(  985): processMsg: InitialState
V/NetworkPolicy(  985): updateIfacesLocked()
,E/WifiStateMachine(  985):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
,D/NetworkManagementService(  985): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  985): processMsg: DefaultState
E/WifiStateMachine(  985):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  985): handleMessage: X
E/WifiStateMachine(  985): handleMessage: E msg.what=131129
E/WifiStateMachine(  985): processMsg: InitialState
E/WifiStateMachine(  985):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: E msg.what=155650
D/WifiController(  985): processMsg: ApStaDisabledState
E/WifiStateMachine(  985):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
,D/WifiController(  985): processMsg: DefaultState
E/WifiStateMachine(  985): handleMessage: X
D/WifiController(  985): handleMessage: X
,W/ResourcesManager( 5924): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  985): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1236): receive(android.intent.action.SCREEN_ON,1,false)
I/CalendarProvider2( 5924): Created com.android.providers.calendar.CalendarAlarmManager@e807cc7(com.htc.providers.calendar.HtcCalendarProvider@1ba3f2f4)
,D/CalendarProvider2( 5924): wait start:true
,D/PMS     (  985): acquireWL(1c4dabdc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  985): releaseWL(1c4dabdc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): acquireWL(2251ebba): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms},
,D/XAN-DPS (  985): prepareColorFade done
,D/XAN-DPS (  985): setBrightness to 0
,D/PMS     (  985): releaseWL(2251ebba): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/DisplayManagerService(  985): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
,I/SensorManager(  985): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@73f4eae
W/SensorService(  985): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  985): disable: get sensor name = CM32181 Light sensor
,V/ActivityManager(  985): Display changed displayId=0
,W/SensorService(  985): pid=985, uid=1000
W/SensorService(  985): Active sensors: size = 3
,W/SensorService(  985): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  985): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  985): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  985): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@73f4eae, eanble = 0, strlen(mName) = 66,
W/SensorService(  985): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  985): Listener[0] = com.htc.smartdim.sensor_eye@4fae377
,W/SensorService(  985): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/CalendarProvider2( 5924): wait end:false
,D/AlarmManager(  985): ACTION_SCREEN_OFF
,I/AlarmManager(  985): [AlarmQueuing] screen off now: 
,I/AlarmManager(  985): [AlarmQueuing] data connection: true
,I/AlarmManager(  985): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  985): stopDataStallAlarm 
E/WifiDataStallTracker(  985): ENABLE_DATA_MONITOR_POLL false Token 0
,E/WifiStateMachine(  985): handleMessage: E msg.what=131167
,E/WifiStateMachine(  985): processMsg: InitialState
D/WifiDisplayAdapter(  985): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  985):     Client/Owner: Client
D/WifiDisplayAdapter(  985):     GroupId: 
D/WifiDisplayAdapter(  985):     Passphrase: 
D/WifiDisplayAdapter(  985):     SessionId: 0
D/WifiDisplayAdapter(  985):     IP Address: }
E/WifiStateMachine(  985):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  985): processMsg: DefaultState
E/WifiStateMachine(  985):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  985):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  985): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  985): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  985): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  985): handleScreenStateChanged Exit: false,
E/WifiStateMachine(  985): handleMessage: X
E/WifiStateMachine(  985): handleMessage: E msg.what=131154
E/WifiStateMachine(  985): processMsg: InitialState
E/WifiStateMachine(  985):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  985): processMsg: DefaultState
E/WifiStateMachine(  985):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  985): handleMessage: X
V/SRS_Proc(  416): ParamSet string: screen_state=off
E/audio_a2dp_hw(  416): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  985): handleMessage: E msg.what=155651
D/WifiController(  985): processMsg: ApStaDisabledState
,D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
D/NetworkPolicy(  985): updateScreenOn: false,
V/NetworkPolicy(  985): updateIfacesLocked()
D/NetworkManagementService(  985): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/ActivityManager(  985): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5953 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager( 1236): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2503d7e6, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  985): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  985): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  985): pid=1236, uid=10041,
W/SensorService(  985): Active sensors: size = 4
W/SensorService(  985): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  985): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  985): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  985): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  985): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2503d7e6, eanble = 1, strlen(mName) = 57
W/SensorService(  985): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  985): Listener[0] = com.htc.smartdim.sensor_eye@4fae377
W/SensorService(  985): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2503d7e6
W/SensorService(  985): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  985): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1329): [EventService] getTotalRam: 1842 Mb,
,D/ContactMessageStore( 1533): start background delete task...,
I/IntentController( 1236): receive(android.intent.action.SCREEN_OFF,1,false),
,D/ContactMessageStore( 1533): size: 0 , 0
,D/ContactMessageStore( 1533): Background delete complete
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  985): acquireWL(34230986): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  985): releaseWL(34230986): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): acquireWL(3761247): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): releaseWL(3761247): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5953): MY_DEBUG = false,
,D/SmartSyncUtils( 5953): isEpsOn(), nState = 0
,D/PMS     (  985): acquireWL(25364b9d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5953 1000 null,
,I/RemoteViews( 1236): setHTCTheme(com.htc.updater,true,33751145),
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/SurfaceControl(  985): Excessive delay in setPowerMode(): 288ms
D/PMS     (  985): Setting HAL interactive mode to false
D/PMS     (  985): Setting HAL interactive mode to false done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  985): Setting HAL auto-suspend mode to true
D/PMS     (  985): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  985): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,I/InputMethodManagerService(  985): screenObserver, isScreenOn=false,
,D/HABCtrl (  985): TPE algorithm. remove timeout.
D/PMS     (  985): OOBE c monitor 11
D/StatusBarManagerService(  985): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  985): Disable input method client, pid=5734
,I/InputMethodManager( 5734): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{35e7d845 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3a88e11c,
I/InputManager(  985): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1236): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  985): acquireWL(3b963812): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(3b963812): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1554): ScreenObserver: OFF
D/NfcService( 1554): applyRouting - 0
,I/RemoteViews( 1236): apply : com.htc.updater 0 21 1 36
,D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/WifiController(  985): battery changed pluggedType: 2
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): Checking...
D/WifiController(  985): handleMessage: E msg.what=155652
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  985): acquireWL(13f78be3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1554 1027 null
D/PMS     (  985): releaseWL(25364b9d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1554): applyRouting -2
D/NfcService( 1554): applyRouting
D/NfcService( 1554): Ignore this applyRouting...
D/PMS     (  985): releaseWL(13f78be3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,W/ContextImpl(  985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,I/PhoneStatusBar( 1236): setImeWindowStatus(false,false)
,D/PowerUI ( 1236): closing low battery warning: level=100
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/SmartDim(  985): Init customizeScreenOffDelayClass error
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5953): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5953): isEpsOn(), nState = 0
,I/ClockController( 1236): stop clock update:screen off
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  985): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  985): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4fae377
W/SensorService(  985): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  985): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  985): pid=985, uid=1000
W/SensorService(  985): Active sensors: size = 3
W/SensorService(  985): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  985): Significant Motion (handle=0x0000000d, connections=1),
W/SensorService(  985): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  985): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4fae377, eanble = 0, strlen(mName) = 35
W/SensorService(  985): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  985): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2503d7e6
W/SensorService(  985): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  985): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  985): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  985): pid=985, uid=1000
W/SensorService(  985): Active sensors: size = 2
W/SensorService(  985): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  985): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  985): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4fae377, eanble = 0, strlen(mName) = 35
W/SensorService(  985): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  985): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2503d7e6,
W/SensorService(  985): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/ActivityThread(  985): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@352b4be4 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  985): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@352b4be4 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  985): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  985): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  985): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  985): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  985): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  985): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  985): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  985): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  985): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  985): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  985): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  985): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  985): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  985): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  985): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  985): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  985): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  985): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  985): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/SensorManager(  985): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4fae377
,I/ActivityManager(  985): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5985 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 5953): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5953): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5953): calcPower(), no data
,D/PowerUsageList:PowerUsageHelper( 5953): MY_DEBUG = false
,D/Process (  985): killProcessQuiet, pid=5383
I/ActivityManager(  985): Killing 5383:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/SmartSyncUtils( 5953): getMobilePolicyEnabled, result = true
,D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  985): ADD_CLIENT: 7
D/WifiService(  985): New client listening to asynchronous messages
,I/ActivityManager(  985): Recipient 5383
,I/ActivityManager(  985): Killing 5628:com.htc.cs.dm/u0a99 (adj 15): empty #17
,D/Process (  985): killProcessQuiet, pid=5628
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5628,
,I/CalendarProvider2( 5924): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 5924): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  985): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6009 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  985): Killing 5650:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,D/Process (  985): killProcessQuiet, pid=5650
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  985): releaseWL(2ca50e61): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  985): Recipient 5650,
,W/ResourcesManager( 6009): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6009): onCreate,
,D/ProviderChangeReceiver( 6009): ---------------------------------------------------
,D/ProviderChangeReceiver( 6009): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  985): killProcessQuiet, pid=5472
I/ActivityManager(  985): Killing 5472:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6009): start to updateAlertNotification!
,I/ActivityManager(  985): Recipient 5472
,D/HtcAlertService( 6009): No fired or scheduled alerts
D/HtcAlertUtils( 6009): -- cancelReminderNotification --
,D/HtcAlertUtils( 6009): broadcastExistReminder!
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1236): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  985): killProcessQuiet, pid=5044
I/ActivityManager(  985): Killing 5044:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5044
,D/ContactMessageStore( 1533): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1533): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  985): acquireWL(1d9bc35e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121766, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{98d033f: PendingIntentRecord{9c1c40c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457487543954, Int=0
D/PMS     (  985): acquireWL(1e845155): PARTIAL_WAKE_LOCK  *backup* 0x1 985 1000 null
,W/BackupManagerService(  985): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  985): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  985): releaseWL(1e845155): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  985): releaseWL(1d9bc35e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  985): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  985): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  985): acquireWL(bdcb76a): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{10024},
V/AlarmManager(  985): sending alarm PendingIntent{12d8945b: PendingIntentRecord{1ccd14f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143183, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{2f85add1: PendingIntentRecord{ab1613b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=152580, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{2c51831c: PendingIntentRecord{384f8b25 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=151553, Int=0
,D/PMS     (  985): acquireWL(3786e036): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1907 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  985): [NET] android_getaddrinfofornet-, err=8
D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024,
D/libc    (  985): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  985): [NET] android_getaddrinfo_proxy+
D/libc    (  985): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  985): releaseWL(bdcb76a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    (  985): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy,
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  985): releaseWL(3786e036): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl(  985): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  985): acquireWL(1c821b37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null,
I/BatteryService(  985): n_update end
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  985): releaseWL(1c821b37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  985): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/PMS     (  985): runPSCheck
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  985): Checking...
D/UsbnetService(  985): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  985): >> updateStatus
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1533): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  985): acquireWL(b3a88a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181766, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{3066560d: PendingIntentRecord{24d8c9c2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=196264, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{2c51831c: PendingIntentRecord{384f8b25 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=212598, Int=0
,V/AlarmManager(  985): sending alarm PendingIntent{bd333d3: PendingIntentRecord{ae98b10 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186323, Int=0,
,D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/libc    (  985): [NET] android_getaddrinfofornet-, err=8
D/libc    (  985): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  985): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  985): [NET] android_getaddrinfo_proxy+
D/libc    (  985): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  985): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  985): acquireWL(2c2f4609): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1907 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): releaseWL(2c2f4609): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1236): Weather sync is On
,D/PMS     (  985): releaseWL(b3a88a4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  985): acquireWL(2b6dc00e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null,
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(2b6dc00e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): Checking...
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  985): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  985): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
D/WifiController(  985): handleMessage: E msg.what=155652
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  985): processMsg: ApStaDisabledState
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  985): processMsg: DefaultState
I/HtcPowerSaver(  985): << updateStatus
D/WifiController(  985): handleMessage: X
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  985): acquireWL(7133a2f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(7133a2f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): handleMessage: E msg.what=155652
D/PMS     (  985): runPSCheck
D/WifiController(  985): processMsg: ApStaDisabledState
D/HtcPowerSaver(  985): Checking...
D/WifiController(  985): processMsg: DefaultState
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): handleMessage: X
I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  985): acquireWL(e44483c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000}
,V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241766, Int=0
,V/AlarmManager(  985): sending alarm PendingIntent{3b7d39c5: PendingIntentRecord{ab1613b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=274703, Int=0
,D/PMS     (  985): acquireWL(27a34a4b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1907 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  985): sending alarm PendingIntent{222bac28: PendingIntentRecord{29fcad41 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457487776508, Int=0
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  985): releaseWL(27a34a4b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): releaseWL(e44483c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1907): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1907): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1907): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1907): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/RemoteViews( 1236): reapply : com.google.android.gms 3 40,
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1907): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1907): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1907): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1907): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5431): Ignoring header User-Agent because its value was null.
,D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1504): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@217129e,
D/HtcUPManager( 1236): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/Process (  985): killProcessQuiet, pid=5406
I/ActivityManager(  985): Killing 5406:com.android.settings/1000 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5406
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  985): acquireWL(203f5c3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  985): n_update end
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  985): releaseWL(203f5c3b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/PMS     (  985): runPSCheck
D/HtcPowerSaver(  985): Checking...
D/WifiController(  985): handleMessage: E msg.what=155652
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): handleMessage: X
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  985): acquireWL(19b66f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
,I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(19b66f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): BroadcastReceiver::onReceive+,
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  985): Checking...
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  985): >> updateStatus
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  985): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  985): acquireWL(3eaa68b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  985): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  985): releaseWL(3eaa68b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/WifiController(  985): battery changed pluggedType: 2
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
,D/PMS     (  985): runPSCheck,
D/HtcPowerSaver(  985): Checking...
I/HtcPowerSaver(  985): >> updateStatus
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  985): acquireWL(45ab196): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(45ab196): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  985): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NotificationService(  985): plugged=true pluggin=true
,D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  985): Checking...
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  985): >> updateStatus
,D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  985): acquireWL(2cbd8117): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=361766, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{38cf2904: PendingIntentRecord{ab1613b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=602497, Int=0
,D/PMS     (  985): acquireWL(bcbdeed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1907 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  985): releaseWL(bcbdeed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  985): releaseWL(2cbd8117): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1533): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1533): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1533): sku_id=118
,D/ContactMessageStore( 1533): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1533): start background delete task...
D/ContactMessageStore( 1533): size: 0 , 0
,D/ContactMessageStore( 1533): Background delete complete
,I/art     (  985): Explicit concurrent mark sweep GC freed 26812(1479KB) AllocSpace objects, 4(600KB) LOS objects, 33% free, 18MB/27MB, paused 1.924ms total 231.176ms
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1907): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1907): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1907): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1907): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1907): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1907): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1907): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1907): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
,E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1236): reapply : com.google.android.gms 2 40
,W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  985): acquireWL(42ade07): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null,
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(42ade07): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  985): updateBatteryInfo
,D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/UsbnetService(  985): onReceive BATTERY_CHANGED
,D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): Checking...
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  985): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  985): acquireWL(1650db34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(1650db34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  985): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1236): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  985): BroadcastReceiver::onReceive-
,D/PMS     (  985): runPSCheck
D/HtcPowerSaver(  985): Checking...
D/WifiController(  985): handleMessage: E msg.what=155652
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
D/WifiController(  985): battery changed pluggedType: 2
I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1907): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1907): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1907): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1907): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1907): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1907): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1907): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1907): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7,
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1236): reapply : com.google.android.gms 4 40
D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  985): acquireWL(6b2b2f6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=661766, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{2ce156f7: PendingIntentRecord{3e7b7964 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457488431533, Int=0
,D/SmartSyncUtils( 5953): isEpsOn(), nState = 0,
,D/WeatherUtility( 1236): Weather sync is On
,D/PMS     (  985): acquireWL(e757cd): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5953 1000 null
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
D/PMS     (  985): releaseWL(6b2b2f6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 5953): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 5953): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 5953): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5953): SettingOnTime = 1457503200000, randomSettingOnTime = 1457502368000
D/SmartSyncScreenOnOffTimeReceiver( 5953): SettingOffTime = 1457568000000, randomSettingOffTime = 1457571889000,
D/SmartSyncScreenOnOffTimeReceiver( 5953): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5953): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5953): bNightModeTurnOffOnce = false
,D/PMS     (  985): acquireWL(14cf0882): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{74a6b93: PendingIntentRecord{e28c7d0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1457488431592, Int=0
,D/PMS     (  985): releaseWL(e757cd): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncDataLinkTurnOffService( 5953): SMARTSYNC_TURN_OFF_NETWORK, current time = 1457488431608, randomOffTime = 1457571889000, newRandomOffTime = 1457571889000,
D/SmartSyncDataLinkTurnOffService( 5953): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1457502368000
,D/SmartSyncUtils( 5953): getMobilePolicyEnabled, result = true,
D/SmartSyncDataLinkTurnOffService( 5953): turnOffMobile bPolicyEnabled = true
,D/PMS     (  985): releaseWL(14cf0882): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/SmartSyncUtils( 5953): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 5953): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  985): getProviders()=[gps, network]
,D/LocationManagerService(  985): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  985): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 5953): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 5953): isCharging status = 5,
,D/SmartSyncDataLinkTurnOffService( 5953): turnOffWifi ui setting = false
,D/PMS     (  985): acquireWL(3c692ace): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  985): releaseWL(3c692ace): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1236): closing low battery warning: level=100
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  985): updateBatteryInfo
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): Checking...
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): handleMessage: E msg.what=155652,
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  985): acquireWL(2d262def): PARTIAL_WAKE_LOCK  *alarm* 0x1 985 1000 WorkSource{1000},
V/AlarmManager(  985): sending alarm PendingIntent{b495b6d: PendingIntentRecord{b6553a2 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806276, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1021766, Int=0
,I/ActivityManager(  985): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6054 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  985): sending alarm PendingIntent{111a90fc: PendingIntentRecord{3f64b385 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457488311481, Int=0
V/AlarmManager(  985): sending alarm PendingIntent{a7125da: PendingIntentRecord{10e16a22 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457488379787, Int=0
,W/ContextImpl( 5953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PowerUsageList:PowerUsageHelper( 5953): MY_DEBUG = false
,D/PMS     (  985): releaseWL(2d262def): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 5953): repeat time = 1457489340071,
D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data
,I/art     (  436): Explicit concurrent mark sweep GC freed 8687(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 393us total 45.189ms
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 307us total 29.133ms,
,I/art     (  436): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 364us total 21.096ms
,I/PowerUsageList:PowerUsageHelper( 5953): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5953): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5953): calcPower(), no data
,E/cutils-trace( 6076): Error opening trace file: Permission denied (13)
I/dex2oat ( 6076): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6076): dex2oat: override thread count:4,
,I/dex2oat ( 6076): dex2oat took 887.958ms (threads: 4),
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6054): ApplicationMonitor {7841b19}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6054): PnsModel {b874a60}: update(): Update registration caused by: alarm,
,I/PushClient( 6054): PnsConfigModel {363c25b7}: <init>(): Use dm-client for provisioning.
,W/System.err( 6054): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6054): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6054): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6054): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  985): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6083 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6083): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6083 dbg=false s=true,
,I/DeviceManagement( 6083): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6083): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6083): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6083): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6083): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b874a60] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6083): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6083): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6083): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6083): SessionStateController: Checking invariants...
,I/DeviceManagement( 6083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6083): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6083): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@b874a60],
,I/DeviceManagement( 6083): WorkflowService: Stopping workflow service
,D/Process (  985): killProcessQuiet, pid=4545
I/ActivityManager(  985): Killing 4545:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6054): PnsModel {b874a60}: update(): Start updating since the registration has expired.,
,I/ActivityManager(  985): Recipient 4545
,W/PushClient( 6054): GCMRegistrator {35218766}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 6054):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6054):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6054):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6054):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6054):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6054):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6054):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6054):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6054):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6054):   
,D/GCM     ( 1907): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  410): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6054): PnsModel {b874a60}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE
E/PushClient( 6054):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6054):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6054):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6054):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6054):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6054):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6054):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6054):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6054):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6054):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6054):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6054):   	... 6 more
E/PushClient( 6054):   
,I/PushClient( 6054): CentralClientRetryPolicy {e807cc7}: scheduleUpdateRetry(): Waiting for network connectivity...
,I/PackageManager(  985):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6054, uid=10071, userID:0,
,I/ActivityManager(  985): Killing 5683:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  985): killProcessQuiet, pid=5683
D/Process (  985): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  985): Recipient 5683
,D/PMS     (  985): acquireWL(16973418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null
I/BatteryService(  985): n_update end
D/PMS     (  985): releaseWL(16973418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  985): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  985): runPSCheck
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): Checking...
I/HtcPowerSaver(  985): >> updateStatus
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): processMsg: ApStaDisabledState
D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  985): acquireWL(12d0ae71): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 985 1000 WorkSource{1000}
V/AlarmManager(  985): sending alarm PendingIntent{c93ce37: PendingIntentRecord{194dbfa4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1081766, Int=0
,V/AlarmManager(  985): sending alarm PendingIntent{3466e456: PendingIntentRecord{ab1613b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1090903, Int=0,
,D/PMS     (  985): acquireWL(19e59cd7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1907 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1907): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1907): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1907): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1907): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1907): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  410): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1907): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  985): releaseWL(19e59cd7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  985): releaseWL(12d0ae71): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1236): Weather sync is On
W/WeatherTimeKeeper( 1236): [refreshWeatherData] no weather data,
,D/PMS     (  985): acquireWL(21d779c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 985 1000 null,
I/BatteryService(  985): n_update end
,D/UsbnetService(  985): BroadcastReceiver::onReceive+
D/PMS     (  985): releaseWL(21d779c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  985): onReceive BATTERY_CHANGED
D/NotificationService(  985): plugged=true pluggin=true
D/UsbnetService(  985):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1236): closing low battery warning: level=100
D/UsbnetService(  985): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  985): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  985): runPSCheck
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  985): Checking...
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  985): >> updateStatus
I/IntentController( 1236): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  985): battery changed pluggedType: 2
D/WifiController(  985): handleMessage: E msg.what=155652
D/WifiController(  985): processMsg: ApStaDisabledState
,D/WifiController(  985): processMsg: DefaultState
D/WifiController(  985): handleMessage: X
D/PowerUI ( 1236): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  985): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  985): << updateStatus
,I/BatteryController( 1236): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  985): User[0] Flushing usage stats to disk
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1907): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1907): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1907): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1907): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1907): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1236): reapply : com.google.android.gms 1 40,
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1907): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1907): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1907): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1907): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1907): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5431): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5431): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5431): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5431): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5431): Ignoring header User-Agent because its value was null.
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5431): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5431): [NET] android_getaddrinfo_proxy+
D/libc    ( 5431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  410): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  410): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  410): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  410): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5431): [NET] android_getaddrinfo_proxy-, NODATA
,TIME-OUT KILL (timeout was 1200000ms)
```
