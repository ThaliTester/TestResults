#### Test 614329799926788_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
I/HtcModeClient( 3172): handler message = 4011
E/HtcModeClient( 3172): Check connection and retry 10 times.
E/cutils-trace( 5735): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5735): ====startRecUseTime====
D/htc.customization.log.level( 5735):  is 
W/CustomizationLogLevel( 5735): Level value is invalid, use default level 2
D/CustomizationManager( 5735):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5735): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5735): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5735): Parsing tag category name = system
I/CustomizationCIDLoader( 5735): Parsing tag category name = application
I/CustomizationCIDLoader( 5735): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5735): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5735): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5735): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5735): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5735): add string-array item, value = 42507
I/CustomizationCIDLoader( 5735): add string-array item, value = 21902
I/CustomizationCIDLoader( 5735): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5735): add string-array item, value = 23420
I/CustomizationCIDLoader( 5735): add string-array item, value = 22299
I/CustomizationCIDLoader( 5735): add string-array item, value = 24002
I/CustomizationCIDLoader( 5735): add string-array item, value = 23210
I/CustomizationCIDLoader( 5735): add string-array item, value = 23205
I/CustomizationCIDLoader( 5735): add string-array item, value = 23806
I/CustomizationCIDLoader( 5735): add string-array item, value = 23430
I/CustomizationCIDLoader( 5735): add string-array item, value = 23408
I/CustomizationCIDLoader( 5735): add string-array item, value = 27205
I/CustomizationCIDLoader( 5735): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5735): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5735):  Read CID file spent 0.091 (s)
D/CustomizationManager( 5735):  All configurations done spent 0.091 (s)
--------- beginning of system
I/ActivityManager(  954): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5735 on display 0
W/asset   (  954): Copying FileAsset 0x557cdfc270 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  954): acquireHCC(cccc6e1): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 954 1000 null
D/PMS     (  954): acquireHCC(1fdf02c7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 954 1000 null
D/PMS     (  954): acquireWL(1dedf01d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null
I/FeedHostManager( 1534): [onPause]
I/FeedProviderManager( 1534): onPause
I/FeedHostManager( 1534): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@27cbd0dc
I/SocialFeedProvider( 1534): +onPause
I/SocialFeedProvider( 1534): -onPause
W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/AnimationUtil(  954): isHTCRecent(ThaliTest/Recent screens.)/13
I/ActivityManager(  954): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5753 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/asset   ( 5753): Copying FileAsset 0xac383f70 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  954): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  954): hiding MENU key
I/TrimMemoryManager( 1534): [trimMemory] 20
,I/WebViewFactory( 5753): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5753): Time to load native libraries: 11 ms (timestamps 1688-1699)
,I/LibraryLoader( 5753): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5753): Binding Chromium to main looper Looper (main, tid 1) {1b89103a}
,I/LibraryLoader( 5753): Expected native library version number "",actual native library version number ""
,I/chromium( 5753): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5753): Initializing chromium process, singleProcess=true
,W/art     ( 5753): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5753): ApplicationContext is null in ApplicationStatus
,W/chromium( 5753): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5753): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5753): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5753): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5753): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5753): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5753): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5753): Local Branch: 
I/Adreno-EGL( 5753): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5753): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5753):                  d74aa161a12b9c6fc6332151
,W/System.err(  954): java.lang.Throwable: stack dump
W/System.err(  954): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  954): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  954): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  954): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  954): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  954): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22901a8d:true
D/BluetoothAdapter( 5753): 858339553: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5753): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5753): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5753): CordovaWebView is running on device made by: HTC
,W/art     ( 5753): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 5753): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5753): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/FindExtension( 5753): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5753): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1cb61e42, mServedView=org.apache.cordova.engine.SystemWebView{1fcf2e53 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@12863390,
I/InputMethodManagerService(  954): Disable input method client, pid=1534
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  954): Enable input method client, pid=5753
,I/PhoneStatusBar( 1238): setImeWindowStatus(false,false)
,D/PMS     (  954): releaseWL(1dedf01d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  954): Displayed com.test.thalitest/.MainActivity: +792ms
,W/XT9_C   ( 1373): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1373): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1373): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1373): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5753): Cannot call determinedVisibility() - never saw a connection for the pid: 5753,
,D/JsMessageQueue( 5753): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5753): JniHelper::setJavaVM(0xab2178f8), pthread_self() = -1403824264
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5753): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e969bf2 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73021f9 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5753): addListener: New listener added - the number of listeners is now 1
,E/WifiTrafficPoller(  954): ADD_CLIENT: 7
D/WifiService(  954): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5753): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5753): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5753): setDiscoveryMode: Discovery mode BLE is supported,
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5753): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5753): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5753): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  954): releaseHCC(cccc6e1): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  954): releaseHCC(1fdf02c7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5753): Initializing JXcore engine
W/jxcore-log( 5753): JXcore engine is ready
,W/jxcore-log( 5753): Starting JXcore engine,
,W/jxcore-log( 5753): Platform android,
W/jxcore-log( 5753): 
W/jxcore-log( 5753): Process ARCH arm
W/jxcore-log( 5753): 
,I/jxcore-log( 5753): JXcore Cordova bridge is ready!
I/jxcore-log( 5753): 
,W/jxcore-log( 5753): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5753): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 5753): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 5753): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5753): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/PMS     (  954): acquireWL(2b184dd8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null,
W/PluginManager( 5753): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1534): [onResume]
I/FeedProviderManager( 1534): onResume
,I/SocialFeedProvider( 1534): +onResume
I/SocialFeedProvider( 1534): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1534): -onResume
I/ConnectivityHelper( 1534): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  954): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  954): hiding MENU key
,D/FindExtension( 1534): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1534): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1238): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  954): Disable input method client, pid=5753
W/IInputConnectionWrapper( 5753): reportFullscreenMode on inactive InputConnection
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  954): Enable input method client, pid=1534
,D/PMS     (  954): releaseWL(2b184dd8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  954): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  954): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  954): hiding MENU key
,D/Process (  954): killProcessQuiet, pid=5568,
I/ActivityManager(  954): Killing 5568:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  954): Recipient 5568
,D/WifiService(  954): Client connection lost with reason: 4
,W/BindingManager( 5753): Cannot call determinedVisibility() - never saw a connection for the pid: 5753,
,W/OpenGLRenderer( 1534): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/HtcModeClient( 3172): handler message = 4011,
E/HtcModeClient( 3172): Check connection and retry 11 times.,
,D/PMS     (  954): acquireWL(9116fee): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10024},
,V/AlarmManager(  954): sending alarm PendingIntent{2c9b5c8f: PendingIntentRecord{2ee903a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=97023, Int=0
D/PMS     (  954): acquireWL(39f42b1c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(9116fee): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  954): releaseWL(39f42b1c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  954): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5812 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  954): Explicit concurrent mark sweep GC freed 25204(1376KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/27MB, paused 1.756ms total 166.309ms
,W/ResourcesManager( 5812): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5812): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5812): MmsConfig.loadMmsSettings
I/ActivityManager(  954): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5841 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5812, uid=10112, userID:0
W/HtcWrapAdjustableCursorFactory( 5841): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 5841): onCreate
V/GetPrviateResource( 5841): GetPrviateResource
D/MmsCustomizationProvider( 5841): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 5841): GetPrviateResource
D/MessageCustFlag( 5841): sense_version=6.0
D/BTAccessoryUtil( 5841): createReceiver
D/BTAccessoryUtil( 5841): registerReceiver return intent = null
D/MessageCustFlag( 5841): sku_id=118
D/MmsCustomizationProvider( 5841): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/HtcBuildUtils( 5841): getRATByHtcTelephonyCapability:1
W/SystemReader( 5841): Cannot find qct_8960_interface, use default value instead
I/Babel_SMS( 5812): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 5812): MmsConfig.loadFromDatabase
E/Babel_SMS( 5812): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5812): MmsConfig.loadFromResources
E/Babel_SMS( 5812): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5812): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
W/Settings( 5812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5812): startup - clean
I/Babel   ( 5812): deleted: false for 0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5812, uid=10112, userID:0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5812, uid=10112, userID:0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5812, uid=10112, userID:0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5812, uid=10112, userID:0
I/PackageManager(  954):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5812, uid=10112, userID:0
W/VideoCapabilities( 5812): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5812): Unsupported mime video/x-ms-wmv
W/Utils   ( 5812): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 5812): Unsupported mime audio/qcelp
W/AudioCapabilities( 5812): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5812): Unsupported mime audio/qcelp
W/VideoCapabilities( 5812): Unsupported mime video/x-ms-wmv
I/VideoCapabilities( 5812): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5812): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5812): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5812): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5812): Unrecognized profile 2130706433 for video/avc
D/Process (  954): killProcessQuiet, pid=5283
I/ActivityManager(  954): Killing 5283:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  954): Recipient 5283
D/Process (  954): killProcessQuiet, pid=4982
I/ActivityManager(  954): Killing 4982:com.google.android.music:main/u0a159 (adj 15): empty #18
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  954): Recipient 4982
D/MediaRouterService(  954): Client com.google.android.music (pid 4982): Died!
I/vclib   ( 5812): onServiceConnected
W/Babel   ( 5812): Attempted to change video mute state without an active call.
I/art     ( 1884): Explicit concurrent mark sweep GC freed 14586(812KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 945us total 67.158ms
,D/Messaging( 5841): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5841): networkCode: 
D/MessageCustFlag( 5841): sku_id=118
D/MmsConfig( 5841): SIE smsPri: null
D/MmsConfig( 5841): networkCode: 
,D/MmsConfig( 5841): packageName: com.htc.vvm.att does not exist,
D/Messaging( 5841): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5841): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5841): 
D/MmsAsyncWorkHandler( 5841): HM tk = 20001
D/ReportIndicatorCache( 5841): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5841): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1b89103a
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/MmsSmsV2Provider( 1483):  slotId = -1000
D/MmsSmsV2Provider( 1483): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 5841): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5841): [DraftCache/1] refresh
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
D/AccFlag ( 1483): sku_id=118
D/MmsConfig( 5841): networkCode: ,
,D/DraftCache( 5841): [DraftCache/136] rebuildCache
,I/Messaging( 5841): mccmnc> ,
D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1483):  slotId = -1000
D/MmsSmsV2Provider( 1483): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1483):  slotId = -1000
,D/MmsSmsV2Provider( 1483): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5841): ViewCache CreatePreloadOnlyConversationList
D/Messaging( 5841): mNeedToUpdateDate2: false
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1483):  slotId = -1000
D/MmsSmsV2Provider( 1483): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5841): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/Jerry   ( 1483): URI_DRAFT
,D/MessageCustFlag( 5841): sense_version=6.0,
D/Jerry   ( 5841): start to preload cursor >>>>>>>
D/DraftCache( 5841): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5841): [DraftCache/136] rebuildCache time: 12
D/MmsAsyncWorkHandler( 5841): ,
D/MmsAsyncWorkHandler( 5841): HM tk = 20002
D/PhoneStorageUtil( 5841): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5841): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5841): createReceiver
D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1483):  slotId = -1000
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1483): sku_id=118
,D/TelephUtils( 1483): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1483): Update uri=content://mms, match=0
V/MmsProvider( 1483): selection=st=129 AND m_type!=134
D/Messaging( 5841): ViewCache CreatePreload
D/Messaging( 5841): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 5841): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5841): TransactionService is going to be woken up.
D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
,D/AccFlag ( 1483): sku_id=118,
V/TransactionService( 5841): 1-Creating TransactionService
,D/Cust_MMSMS( 5841): _has_set_default_values_2=true,
,D/MsgPreferenceUtils( 5841): def_index: 0
,D/MsgPreferenceUtils( 5841): globalIndex = 1
,V/TransactionService( 5841): onStartCommand: 1,
D/MmsSystemEventReceiver( 5841): unRegisterForConnectionStateChanges
V/TransactionService( 5841): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5841): Loading previous transactions.
,D/MsgPreferenceUtils( 5841): phone state: true
D/MsgPreferenceUtils( 5841): sd state: false
D/MsgPreferenceUtils( 5841): vIndex = 0
,D/TelephUtils( 1483): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1483): device_type: 1
,D/TransactionService( 5841): Force clearing mTransactionList
,D/TransactionService( 5841): Force set service start id to 1
V/TransactionService( 5841): stopSelfIfIdle: unRegisterForConnectionStateChanges,
,D/MmsSystemEventReceiver( 5841): unRegisterForConnectionStateChanges
V/TransactionService( 5841): Destroying TransactionService
D/TransactionService( 5841): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5841): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3172): handler message = 4011
,E/HtcModeClient( 3172): Check connection and retry 12 times.
,I/HtcModeClient( 3172): handler message = 4011,
,E/HtcModeClient( 3172): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3172): Don't start project servcice,
,D/HtcModeClient( 3172): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3172): connectState: CONNECTION_READY = false
,D/SilentMusic( 3172): call stop
D/HtcModeClient( 3172): close connection
W/HtcModeClient( 3172): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3172): read the terminate packet, so break
,D/Process (  954): killProcessQuiet, pid=3172
,I/ActivityManager(  954): Killing 3172:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 3172,
,I/ActivityManager(  954): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5894 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  954): acquireWL(10d93db9): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10076},
V/AlarmManager(  954): sending alarm PendingIntent{1363d5fe: PendingIntentRecord{2d29b15f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457077228312, Int=60000
D/PMS     (  954): releaseWL(10d93db9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5894): SMSBackupAgentService started
,D/SMSBackup( 5894): Checking restore status
D/SMSBackup( 5894): Restore complete
,D/SMSBackup( 5894): cancelCheckAlarm
,D/SMSBackup( 5894): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  954): killProcessQuiet, pid=5408
I/ActivityManager(  954): Killing 5408:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5408
,I/PMS     (  954): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  954): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@865d83c,
D/ActivityManager(  954): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{2ac6fc75 #9 A=.Prism U=0 sz=1}
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  954): mWirelessDisplayManager is null
W/SensorService(  954): disable: get sensor name = Accelerometer Sensor
W/PMS     (  954): mWirelessDisplayManager is still null
W/SensorService(  954): pid=954, uid=1000
I/PMS     (  954): Sleeping (uid 1000)...
W/SensorService(  954): Active sensors: size = 4
D/XAN-DPS (  954): prepareColorFade 1
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/PMN     (  954): goingToSleep
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@865d83c, eanble = 0, strlen(mName) = 90
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  954): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@115b3957
W/SensorService(  954): Listener[1] = com.htc.smartdim.sensor_eye@63f6a50
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  954): acquireWL(f23540a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 954 1000 null
,W/HtcLockScreen( 1238): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  954): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  954): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL(  954): Build Date: 03/09/15 Mon
I/Adreno-EGL(  954): Local Branch: 
I/Adreno-EGL(  954): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  954): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  954):                  d74aa161a12b9c6fc6332151
,W/PMN     (  954): goingToSleep done
I/FeedHostManager( 1534): [onPause]
I/FeedProviderManager( 1534): onPause
I/FeedHostManager( 1534): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@27cbd0dc
,I/SocialFeedProvider( 1534): +onPause
I/SocialFeedProvider( 1534): -onPause
,W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/PMS     (  954): releaseWL(f23540a): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  954): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5918 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  954): ACTION_SCREEN_ON
I/AlarmManager(  954): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  954): [AlarmQueuing] done recovering
I/AlarmManager(  954): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  954): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  954): handleMessage: E msg.what=131167
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  954): processMsg: DefaultState
,E/WifiStateMachine(  954):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  954):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,D/WifiStateMachine(  954): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  954): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  954): handleScreenStateChanged Exit: true
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131154
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131127
E/WifiStateMachine(  954): processMsg: InitialState
,E/WifiStateMachine(  954):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131129
E/WifiStateMachine(  954): processMsg: InitialState
V/SRS_Proc(  400): ParamSet string: screen_state=on
E/WifiStateMachine(  954):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  954):  DefaultState !CMD_CLEAR_BLACKLIST 0 0,
E/WifiStateMachine(  954): handleMessage: X
D/WifiController(  954): handleMessage: E msg.what=155650
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/NetworkPolicy(  954): updateScreenOn: false
D/WifiController(  954): handleMessage: X
,V/NetworkPolicy(  954): updateIfacesLocked()
D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/NetworkManagementService(  954): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 5918): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 5918): Created com.android.providers.calendar.CalendarAlarmManager@1a4a1c5c(com.htc.providers.calendar.HtcCalendarProvider@115a4b65)
,I/IntentController( 1238): receive(android.intent.action.SCREEN_ON,1,false)
,D/CalendarProvider2( 5918): wait start:true
,D/PMS     (  954): acquireWL(28c7b04f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1816 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(20d853dc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1816 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): releaseWL(28c7b04f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(20d853dc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  954): prepareColorFade done
,D/XAN-DPS (  954): setBrightness to 0
,I/SensorManager(  954): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@115b3957
I/DisplayManagerService(  954): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  954): Display changed displayId=0,
D/DotMatrix( 1322): [EventService]  onDisplayChanged: 0
W/SensorService(  954): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1322): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/AlarmManager(  954): ACTION_SCREEN_OFF
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  954): pid=954, uid=1000
W/SensorService(  954): Active sensors: size = 3
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@115b3957, eanble = 0, strlen(mName) = 67
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  954): Listener[0] = com.htc.smartdim.sensor_eye@63f6a50
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/AlarmManager(  954): [AlarmQueuing] screen off now: 
I/AlarmManager(  954): [AlarmQueuing] data connection: true
I/AlarmManager(  954): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  954): stopDataStallAlarm 
E/WifiDataStallTracker(  954): ENABLE_DATA_MONITOR_POLL false Token 0
E/WifiStateMachine(  954): handleMessage: E msg.what=131167
E/WifiStateMachine(  954): processMsg: InitialState
E/WifiStateMachine(  954):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  954):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,D/WifiStateMachine(  954): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  954): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  954): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  954):     Client/Owner: Client
D/WifiDisplayAdapter(  954):     GroupId: 
D/WifiDisplayAdapter(  954):     Passphrase: 
D/WifiDisplayAdapter(  954):     SessionId: 0
D/WifiDisplayAdapter(  954):     IP Address: }
D/WifiStateMachine(  954): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  954): handleScreenStateChanged Exit: false
E/WifiStateMachine(  954): handleMessage: X
E/WifiStateMachine(  954): handleMessage: E msg.what=131154
E/WifiStateMachine(  954): processMsg: InitialState
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  954):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  954): processMsg: DefaultState
E/WifiStateMachine(  954):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  954): handleMessage: X
,D/WifiController(  954): handleMessage: E msg.what=155651
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,D/NetworkPolicy(  954): updateScreenOn: false
V/NetworkPolicy(  954): updateIfacesLocked()
D/NetworkManagementService(  954): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/CalendarProvider2( 5918): wait end:false
,I/ActivityManager(  954): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager( 1238): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@28ed7709, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  954): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  954): pid=1238, uid=10041
W/SensorService(  954): Active sensors: size = 4
W/SensorService(  954): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@28ed7709, eanble = 1, strlen(mName) = 57
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  954): Listener[0] = com.htc.smartdim.sensor_eye@63f6a50,
W/SensorService(  954): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@28ed7709
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1322): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1483): start background delete task...
I/IntentController( 1238): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1483): size: 0 , 0
,D/ContactMessageStore( 1483): Background delete complete
,D/PMS     (  954): acquireWL(1584d1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1816 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): acquireWL(2a287261): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1816 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  954): releaseWL(1584d1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): releaseWL(2a287261): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1238): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1238): apply : com.htc.updater 1 24 1 36,
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 5946): MY_DEBUG = false
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/SurfaceControl(  954): Excessive delay in setPowerMode(): 296ms
D/PMS     (  954): Setting HAL interactive mode to false
,D/PMS     (  954): Setting HAL interactive mode to false done
D/PMS     (  954): Setting HAL auto-suspend mode to true
D/PMS     (  954): Setting HAL auto-suspend mode done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
W/HtcSystemUPManager(  954): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/SmartSyncUtils( 5946): isEpsOn(), nState = 0
I/InputMethodManagerService(  954): screenObserver, isScreenOn=false
I/InputManager(  954): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1238): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/StatusBarManagerService(  954): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  954): Disable input method client, pid=1534
,D/HABCtrl (  954): TPE algorithm. remove timeout.
D/PMS     (  954): OOBE c monitor 11,
,I/PhoneStatusBar( 1238): setImeWindowStatus(false,false)
,D/NfcService( 1497): ScreenObserver: OFF
D/NfcService( 1497): applyRouting - 0
,D/PMS     (  954): acquireWL(2f94274): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1497 1027 null
D/NfcService( 1497): applyRouting -2
D/NfcService( 1497): applyRouting
D/NfcService( 1497): Ignore this applyRouting...
D/PMS     (  954): acquireWL(1018d39d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
,I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(2f94274): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  954): releaseWL(1018d39d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1238): closing low battery warning: level=100
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  954): handleMessage: X
D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): runPSCheck
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
,D/PMS     (  954): acquireWL(337a2012): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5946 1000 null
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
I/ClockController( 1238): stop clock update:screen off
W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  954): Init customizeScreenOffDelayClass error
D/PMS     (  954): releaseWL(337a2012): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5946): isEpsOn(), nState = 0
D/SmartSyncUtils( 5946): isEpsOn(), nState = 0
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/SensorManager(  954): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@63f6a50
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  954): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  954): pid=954, uid=1000
W/SensorService(  954): Active sensors: size = 3
,W/SensorService(  954): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@63f6a50, eanble = 0, strlen(mName) = 35
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  954): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@28ed7709
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  954): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  954): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  954): pid=954, uid=1000
,W/SensorService(  954): Active sensors: size = 2
W/SensorService(  954): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  954): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  954): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@63f6a50, eanble = 0, strlen(mName) = 35
W/SensorService(  954): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  954): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@28ed7709
W/SensorService(  954): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  954): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@63f6a50
E/ActivityThread(  954): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@544d449 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  954): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@544d449 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  954): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  954): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  954): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  954): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  954): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  954): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  954): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  954): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  954): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
,E/ActivityThread(  954): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  954): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  954): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  954): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  954): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  954): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  954): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  954): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5979 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 5946): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5946): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5946): calcPower(), no data,
,D/Process (  954): killProcessQuiet, pid=5627
,I/ActivityManager(  954): Killing 5627:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 5946): getMobilePolicyEnabled, result = true
,D/WifiService(  954): New client listening to asynchronous messages
,E/WifiTrafficPoller(  954): ADD_CLIENT: 7
,I/ActivityManager(  954): Recipient 5627
,D/PowerUsageList:PowerUsageHelper( 5946): MY_DEBUG = false
,D/Process (  954): killProcessQuiet, pid=5649
,I/ActivityManager(  954): Killing 5649:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 5918): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5918): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  954): Recipient 5649
,I/ActivityManager(  954): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6004 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  954): killProcessQuiet, pid=5495
,I/ActivityManager(  954): Killing 5495:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5495
,D/PMS     (  954): releaseWL(1122d7e3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/ResourcesManager( 6004): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6004): onCreate,
,D/ProviderChangeReceiver( 6004): ---------------------------------------------------
D/ProviderChangeReceiver( 6004): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  954): killProcessQuiet, pid=5430
,I/ActivityManager(  954): Killing 5430:com.android.settings/1000 (adj 15): empty #17
D/HtcAlertService( 6004): start to updateAlertNotification!
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  954): Recipient 5430,
,D/HtcAlertService( 6004): No fired or scheduled alerts,
,D/HtcAlertUtils( 6004): -- cancelReminderNotification --,
,D/HtcAlertUtils( 6004): broadcastExistReminder!,
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1238): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  954): killProcessQuiet, pid=5082,
I/ActivityManager(  954): Killing 5082:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5082,
,D/PMS     (  954): acquireWL(24b40c99): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{13d62b5e: PendingIntentRecord{1c1b4b3f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457077244923, Int=0
D/PMS     (  954): acquireWL(3a466c0c): PARTIAL_WAKE_LOCK  *backup* 0x1 954 1000 null
D/PMS     (  954): releaseWL(24b40c99): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  954): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  954): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  954): releaseWL(3a466c0c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/ContactMessageStore( 1483): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1483): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  954): acquireWL(222fd955): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139112, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{f559f6a: PendingIntentRecord{14035c5b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142651, Int=0
,D/PMS     (  954): releaseWL(222fd955): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1238): Weather sync is On
,W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  954): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  954): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  954): acquireWL(14f43cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{10024}
V/AlarmManager(  954): sending alarm PendingIntent{3661b5d1: PendingIntentRecord{2ee903a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=169586, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{187322eb: PendingIntentRecord{2a6ba848 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=148006, Int=0
D/PMS     (  954): acquireWL(1da64836): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  954): [NET] android_getaddrinfofornet-, err=8
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  954): releaseWL(14f43cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  954): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  954): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): releaseWL(1da64836): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): acquireWL(19916337): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(19916337): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
,D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: X
,D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1483): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1238): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1446): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@25491087
,D/Process (  954): killProcessQuiet, pid=4605
I/ActivityManager(  954): Killing 4605:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/HtcUPManager( 1238): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 4605
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  954): acquireWL(22ac30a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3cfade0d: PendingIntentRecord{3186b1c2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=195351, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199113, Int=0,
D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  954): sending alarm PendingIntent{187322eb: PendingIntentRecord{2a6ba848 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=229605, Int=0
D/libc    (  954): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  954): sending alarm PendingIntent{1e8efbd3: PendingIntentRecord{2bcdb310 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185829, Int=0
,D/libc    (  954): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  954): acquireWL(21844e09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  954): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  954): [NET] android_getaddrinfo_proxy+
D/libc    (  954): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  954): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): releaseWL(22ac30a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1238): Weather sync is On
,W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
,D/PMS     (  954): releaseWL(21844e09): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  954): acquireWL(3912280e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  954): n_update end
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(3912280e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652,
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): processMsg: DefaultState
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1238): closing low battery warning: level=100
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  954): acquireWL(1dc3822f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(1dc3822f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1238): closing low battery warning: level=100
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  954): updateBatteryInfo
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
,D/WifiController(  954): handleMessage: X
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  954): acquireWL(1d42f03c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259113, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{251ac1c5: PendingIntentRecord{2ee903a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=314709, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{d10124b: PendingIntentRecord{266cd428 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457077462402, Int=0
D/PMS     (  954): acquireWL(3eab541): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy,
D/PMS     (  954): releaseWL(1d42f03c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7,
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
D/WeatherUtility( 1238): Weather sync is On
W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
,D/PMS     (  954): releaseWL(3eab541): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  954): acquireWL(1f6f2ae6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(1f6f2ae6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  954): plugged=true pluggin=true
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): handleMessage: E msg.what=155652
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  954): battery changed pluggedType: 2
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  954): processMsg: ApStaDisabledState
,D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1238): closing low battery warning: level=100
D/HtcPowerSaver(  954): updateBatteryInfo
D/PMS     (  954): runPSCheck
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
,D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1238): reapply : com.google.android.gms 2 40
,E/PlayEventLogger( 5454): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5454): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5454): Ignoring header User-Agent because its value was null.
,D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5454): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5454): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5454): [NET] android_getaddrinfo_proxy+
D/libc    ( 5454): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5454): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  954): acquireWL(24919758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/BatteryService(  954): n_update end
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): releaseWL(24919758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): updateBatteryInfo
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): runPSCheck
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  954): Checking...
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  954): >> updateStatus
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  954): << updateStatus
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  954): handleMessage: X
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  954): acquireWL(142a70b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(142a70b1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: E msg.what=155652
D/PMS     (  954): runPSCheck
D/WifiController(  954): processMsg: ApStaDisabledState
D/HtcPowerSaver(  954): Checking...,
D/WifiController(  954): processMsg: DefaultState
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  954): acquireWL(1e4e1996): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(1e4e1996): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  954): updateBatteryInfo
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1238): closing low battery warning: level=100
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): handleMessage: X
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1483): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1483): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1483): sku_id=118
D/ContactMessageStore( 1483): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1483): start background delete task...
,D/ContactMessageStore( 1483): size: 0 , 0
,D/ContactMessageStore( 1483): Background delete complete
,D/PMS     (  954): acquireWL(1310c917): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379112, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{1a34d104: PendingIntentRecord{2ee903a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=631755, Int=0
,D/PMS     (  954): acquireWL(2d4466ed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  954): releaseWL(1310c917): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,D/WeatherUtility( 1238): Weather sync is On
,W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
,D/PMS     (  954): releaseWL(2d4466ed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  954): acquireWL(25ca3922): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
,D/UsbnetService(  954): BroadcastReceiver::onReceive+,
D/PMS     (  954): releaseWL(25ca3922): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954): onReceive BATTERY_CHANGED
,D/NotificationService(  954): plugged=true pluggin=true,
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): battery changed pluggedType: 2
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  954): runPSCheck
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  954): Checking...
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): >> updateStatus
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  954): Explicit concurrent mark sweep GC freed 26460(1501KB) AllocSpace objects, 4(540KB) LOS objects, 33% free, 18MB/27MB, paused 1.860ms total 192.880ms,
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5454): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5454): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5454): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5454): [NET] android_getaddrinfofornet-, err=8
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5454): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5454): [NET] android_getaddrinfo_proxy+
D/libc    ( 5454): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1238): reapply : com.google.android.gms 3 40
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5454): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): acquireWL(10708334): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(10708334): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  954): << updateStatus
D/PowerUI ( 1238): closing low battery warning: level=100
,D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(3619e55d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(3619e55d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): onReceive BATTERY_CHANGED
,D/WifiController(  954): battery changed pluggedType: 2
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/PMS     (  954): runPSCheck
D/WifiController(  954): handleMessage: E msg.what=155652
D/HtcPowerSaver(  954): Checking...
D/WifiController(  954): processMsg: ApStaDisabledState
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): processMsg: DefaultState
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): << updateStatus
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(2fd72ed2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null,
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(2fd72ed2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  954): updateBatteryInfo
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1238): closing low battery warning: level=100,
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: E msg.what=155652
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  954): processMsg: ApStaDisabledState
I/HtcPowerSaver(  954): << updateStatus
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5454): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5454): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5454): Ignoring header User-Agent because its value was null.
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5454): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5454): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5454): [NET] android_getaddrinfo_proxy+
D/libc    ( 5454): [NET] android_getaddrinfo_proxy get netid:0
,I/RemoteViews( 1238): reapply : com.google.android.gms 3 40
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5454): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  954): acquireWL(33d52164): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 954 1000 WorkSource{1000},
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=679113, Int=0,
V/AlarmManager(  954): sending alarm PendingIntent{3943dfcd: PendingIntentRecord{35a4f082 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457078133669, Int=0
,D/SmartSyncUtils( 5946): isEpsOn(), nState = 0
,D/PMS     (  954): acquireWL(1f0e3393): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5946 1000 null
,D/PMS     (  954): releaseWL(33d52164): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 5946): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5946): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/WeatherUtility( 1238): Weather sync is On
W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 5946): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5946): SettingOnTime = 1457157600000, randomSettingOnTime = 1457157516000
D/SmartSyncScreenOnOffTimeReceiver( 5946): SettingOffTime = 1457136000000, randomSettingOffTime = 1457141700000
,D/SmartSyncScreenOnOffTimeReceiver( 5946): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5946): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5946): bNightModeTurnOffOnce = false
,D/PMS     (  954): releaseWL(1f0e3393): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  954): acquireWL(374efd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  954): releaseWL(374efd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  954): updateBatteryInfo
D/PowerUI ( 1238): closing low battery warning: level=100
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  954): Checking...
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  954): >> updateStatus
D/UsbnetService(  954): BroadcastReceiver::onReceive-
,D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: ApStaDisabledState
,D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  954): acquireWL(24bbabc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/BatteryService(  954): n_update end
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): releaseWL(24bbabc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): updateBatteryInfo
D/NotificationService(  954): plugged=true pluggin=true
D/PMS     (  954): runPSCheck
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
,D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1238): closing low battery warning: level=100
I/HtcPowerSaver(  954): << updateStatus
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  954): acquireWL(38b592ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
D/UsbnetService(  954): BroadcastReceiver::onReceive+
I/BatteryService(  954): n_update end
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/PMS     (  954): releaseWL(38b592ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  954): plugged=true pluggin=true
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  954): updateBatteryInfo
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/PowerUI ( 1238): closing low battery warning: level=100
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  954): battery changed pluggedType: 2,
D/WifiController(  954): handleMessage: E msg.what=155652
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): processMsg: DefaultState
D/WifiController(  954): handleMessage: X
,D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  954): << updateStatus
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  954): acquireWL(115e75ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 954 1000 WorkSource{1000}
V/AlarmManager(  954): sending alarm PendingIntent{2d84ba9: PendingIntentRecord{adbe52e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805202, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{3508dce2: PendingIntentRecord{df1873 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039113, Int=0
V/AlarmManager(  954): sending alarm PendingIntent{130138fc: PendingIntentRecord{2ee903a5 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1212199, Int=0
D/PMS     (  954): acquireWL(5ca3b85): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  954): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6052 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  954): sending alarm PendingIntent{231c0dda: PendingIntentRecord{fc6820b com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457077948031, Int=0
,V/AlarmManager(  954): sending alarm PendingIntent{12a6e8e8: PendingIntentRecord{21c831e9 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457078081646, Int=0
,D/PMS     (  954): releaseWL(5ca3b85): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5946): MY_DEBUG = false
,D/PMS     (  954): releaseWL(115e75ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 5946): repeat time = 1457079233148,
D/WeatherUtility( 1238): Weather sync is On
W/WeatherTimeKeeper( 1238): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 5946): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5946): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5946): calcPower(), no data
,E/cutils-trace( 6076): Error opening trace file: Permission denied (13),
I/dex2oat ( 6076): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6076): dex2oat: override thread count:4
,I/dex2oat ( 6076): dex2oat took 539.192ms (threads: 4),
,I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): Htc_DEBUG_flag:          false,
I/PushClient( 6052): ApplicationMonitor {1c5dc4c7}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6052): PnsModel {36e7f606}: update(): Update registration caused by: alarm,
,I/PushClient( 6052): PnsConfigModel {c0dd7d5}: <init>(): Use dm-client for provisioning.
,W/System.err( 6052): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6052): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6052): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6052): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  954): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6083 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6083): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6083 dbg=false s=true,
,I/DeviceManagement( 6083): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6083): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6083): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6083): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6083): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@332938e1] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6083): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6083): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6083): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6083): SessionStateController: Checking invariants...
,I/DeviceManagement( 6083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6083): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6083): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6083): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@332938e1],
,I/DeviceManagement( 6083): WorkflowService: Stopping workflow service
,D/Process (  954): killProcessQuiet, pid=5680
I/ActivityManager(  954): Killing 5680:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5680,
,I/PushClient( 6052): PnsModel {36e7f606}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  954): Killing 5527:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  954): killProcessQuiet, pid=5527
D/Process (  954): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  954): Recipient 5527
,I/UsageStatsService(  954): User[0] Flushing usage stats to disk,
,D/PMS     (  954): acquireWL(3b03a18a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 954 1000 null
I/BatteryService(  954): n_update end
D/PMS     (  954): releaseWL(3b03a18a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  954): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  954): updateBatteryInfo
D/UsbnetService(  954): onReceive BATTERY_CHANGED
D/NotificationService(  954): plugged=true pluggin=true
D/UsbnetService(  954):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  954): runPSCheck
D/UsbnetService(  954): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  954): Checking...
I/HtcPowerSaver(  954): >> updateStatus
D/WifiController(  954): handleMessage: E msg.what=155652
D/WifiController(  954): processMsg: ApStaDisabledState
D/WifiController(  954): battery changed pluggedType: 2
D/WifiController(  954): processMsg: DefaultState
D/PowerUI ( 1238): closing low battery warning: level=100
D/WifiController(  954): handleMessage: X
D/PowerUI ( 1238): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  954): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1322): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  954): << updateStatus
D/DotMatrix( 1322): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1238): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1238): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5454): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
,E/PlayEventLogger( 5454): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5454): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1322): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1322): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5454): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5454): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5454): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5454): [NET] android_getaddrinfo_proxy+
D/libc    ( 5454): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5454): [NET] android_getaddrinfo_proxy-, NODATA
,I/RemoteViews( 1238): reapply : com.google.android.gms 4 40
,TIME-OUT KILL (timeout was 1200000ms)
```
