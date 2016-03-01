#### Test 6122644500803c8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/art     ( 2109): Explicit concurrent mark sweep GC freed 17346(974KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 2.018ms total 45.267ms
,D/AndroidRuntime( 6018): 
D/AndroidRuntime( 6018): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6018): CheckJNI is OFF
D/AndroidRuntime( 6018): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1065): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1946): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1065): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1065): setTaskToReturnTo : TaskRecord{79b41af #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1065): setTaskToReturnTo : TaskRecord{79b41af #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1065): AppWindowTokenEx init.. 
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/ActivityManager( 1065): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6047 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1065): Focus left window: Window{e2f5cd6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2066): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 6018): Shutting down VM
V/ActivityManager( 1065): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{198b9380 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{3c5efdb9 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6047): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/WebViewFactory( 6047): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6047): Loading: webviewchromium
I/LibraryLoader( 6047): Time to load native libraries: 3 ms (timestamps 5682-5685)
I/LibraryLoader( 6047): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6047): Binding Chromium to main looper Looper (main, tid 1) {153e63a}
I/LibraryLoader( 6047): Expected native library version number "",actual native library version number ""
I/chromium( 6047): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6047): Initializing chromium process, renderers=0
W/art     ( 6047): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6047): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  327): registerClient() client 0xb57bedc0, uid 10311
,W/chromium( 6047): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6047): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6047): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1065): Message: 20
D/BluetoothManagerService( 1065): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ad878c1:true
D/BluetoothAdapter( 6047): 733668075: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6047): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6047): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6047): Build Date: 12/12/14 금
I/Adreno-EGL( 6047): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6047): Remote Branch: 
I/Adreno-EGL( 6047): Local Patches: 
I/Adreno-EGL( 6047): Reconstruct Branch: 
W/chromium( 6047): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6047): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6047): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6047): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6047): [generateLayout] setColorNavigationBar => color=0x ff000001
,D/PhoneWindowEx( 6047): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6047): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 6047): CordovaWebView is running on device made by: LGE
,W/art     ( 6047): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6047): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6047): Render dirty regions requested: true
I/OpenGLRenderer( 6047): Initialized EGL, version 1.4
D/OpenGLRenderer( 6047): Enabling debug mode 0
,D/Atlas   ( 6047): Validating map...
,W/ActivityManager( 1065): Activity pause timeout for ActivityRecord{77879bc u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1065): check instance of lgWin Window{317b6733 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6047): LgDataFeature() Constructor: none
D/LgDataFeature( 6047): LgDataFeature() Constructor Done, null
,D/WindowManager( 1065): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework]( 1065): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx( 1065): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1065): setLGSystemUiVisibility(0x0)
I/[SystemUI]NavigationThemeResource( 1448): notify navigation bar color(0xfff5f5f5)
D/StatusBarManagerServiceEx( 1065): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1065): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30170f51,  pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1448): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1448):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1448): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1065): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/InputDispatcher( 1065): Focus entered window: Window{317b6733 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputMethodManagerService( 1065): setImestate : 0
,I/ActivityManager( 1065): Displayed com.test.thalitest/.MainActivity: +636ms (total +737ms)
,I/Timeline( 1065): Timeline: Activity_windows_visible id: ActivityRecord{77879bc u0 com.test.thalitest/.MainActivity t4} time:96136
W/IInputConnectionWrapper( 6047): showStatusIcon on inactive InputConnection
I/Timeline( 6047): Timeline: Activity_idle id: android.os.BinderProxy@3c3ba2b6 time:96147
,W/IInputConnectionWrapper( 6047): getTextBeforeCursor on inactive InputConnection
E/b       ( 1686): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6047): getTextAfterCursor on inactive InputConnection
,I/chromium( 6047): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6047): 
,D/JsMessageQueue( 6047): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6047): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6047): 
,D/jxcore_app_log( 6047): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435009664
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264c32cb added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6047): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Discovery mode: WIFI
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196930a7 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6047): addListener: New listener added - the number of listeners is now 1
,D/WifiService( 1065): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6047): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6047): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): setDiscoveryMode: WIFI -> BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6047): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6047): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6047): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 6047): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6047): Initializing JXcore engine
W/jxcore-log( 6047): JXcore engine is ready
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 97796502413; DSPS: 3345722; Offset : -4323414141
,W/Thread-707( 6119): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7473]" dev="sockfs" ino=7473 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-707( 6119): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3271 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-707( 6119): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9882]" dev="sockfs" ino=9882 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-707( 6119): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-707( 6119): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[29460]" dev="sockfs" ino=29460 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6047): Starting JXcore engine
,W/jxcore-log( 6047): Platform android
W/jxcore-log( 6047): 
W/jxcore-log( 6047): Process ARCH arm
W/jxcore-log( 6047): 
,I/jxcore-log( 6047): JXcore Cordova bridge is ready!
I/jxcore-log( 6047): 
W/jxcore-log( 6047): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6047): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/rmt_storage(  313): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  313): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  313): wakelock acquired: 1, error no: 42
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  313): 
,I/rmt_storage(  313): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  884): [IMS_FATAL]| 3347 | 902 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6047): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 6047): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 6047): BLE multiple advertisement supported
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): My device name is: LGE-LG-D855
I/jxcore-log( 6047): 
,I/MusicWidget( 2602): mDelayedStopHandler : unbind
,I/MusicBrowser( 2211): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2211): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2211): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2211): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2211): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2211): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,I/MediaFocusControl( 1065):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1d3a7378com.lge.music.MediaPlaybackService$5@7e1ea51
D/MusicBrowser( 2211): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3fe2c2c7
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2211): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2211): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2211): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2211): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2211): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2211): reset
V/MediaPlayer[Native]( 2211): setListener
V/MediaPlayer[Native]( 2211): disconnect
V/MediaPlayer[Native]( 2211): destructor
,V/AudioFlinger(  327): releasing 13 from 2211 for -1,
,V/AudioFlinger(  327):  decremented refcount to 0
,V/AudioFlinger(  327): purging stale effects
V/MediaPlayer[Native]( 2211): disconnect,
D/MusicBrowser( 2211): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,I/SmartShareClient( 2211): [SmartShareManagerClient] smartshare client supported version code: 305000
,I/SmartShareClient( 2211): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2211): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2211): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2211): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2211): [SmartShareManagerClient] unregisterListener: 1010541238
W/SmartShareClient( 2211): [SmartShareManagerClient] unregisterListener invalid listener: 1010541238
I/SmartShareClient( 2211): [SmartShareManagerClient] terminate service: 2211/MediaPlaybackService/315799909
E/HomeCloudIF( 2211): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2211): [SmartShareManagerClient] unbindService context:android.app.Application@1fbbebb7
V/CloudHub( 2211): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2211): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2211): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2211): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,I/ActivityManager( 1065): Killing 5532:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/CloudHub( 2211): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
W/libprocessgroup( 1065): failed to open /acct/uid_10011/pid_5532/cgroup.procs: No such file or directory
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6047): 
,I/io.jxcore.node.ConnectivityInfo( 6047): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6047):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6047):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6047):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 6047):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6047):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 6047):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 6047):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 6047):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 6047): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
I/jxcore-log( 6047): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6047): 
I/jxcore-log( 6047): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6047): 
I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6047): 
I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6047): 
I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6047): 
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,I/jxcore-log( 6047): 
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6047): 
,V/AlarmManager( 1065): RTC_WAKEUP set : Alarm{c0cd225 type 0 when 1456845349369 com.android.vending} when 1456845349369
,W/ContextImpl( 4226): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1065): Menu title from STK is T-Mobile
,I/jxcore-log( 6047): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6047): 
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6047): Unit Test app is loaded
I/jxcore-log( 6047): 
I/chromium( 6047): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 6047): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 6047): 
,D/Finsky  ( 5643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5643): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5643): [1] 5.onFinished: Scheduling replication attempt 2.
I/CloudHub( 2211): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19996
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 117799038186; DSPS: 4001165; Offset : -4323413018
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1448): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1448): On Skip Timer : true
,D/WifiController( 1065): battery changed pluggedType: 2
,D/LEDHandler( 1946): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1946): Battery Level Remaining: 100%
D/LEDHandler( 1946): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1448): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1448): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1448): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 5915): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/CloudHub( 2211): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2211): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/PowerManagerServiceEx( 1065): acquireWakeLockInternal: lock=385494655, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1065
,V/AlarmManager( 1065): RTC_WAKEUP set : Alarm{2acf8e95 type 0 when 1456845372118 com.android.vending} when 1456845372118
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1065): releaseWakeLockInternal: lock=385494655 [*alarm*], flags=0x0
,V/SIM_STK ( 1065): Menu title from STK is T-Mobile
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5643): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5643): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 137802162659; DSPS: 4656627; Offset : -4323401417
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 157804279422; DSPS: 5312057; Offset : -4323420780
,V/AlarmManager( 1065): RTC_WAKEUP set : Alarm{329c427c type 0 when 1456845396121 com.android.vending} when 1456845396121
,V/SIM_STK ( 1065): Menu title from STK is T-Mobile
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5643): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5643): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 177806827694; DSPS: 5967500; Offset : -4323405467
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1065): ELAPSED_WAKEUP set : Alarm{68338fe type 2 when 143163 com.google.android.gms} when 143163
V/AlarmManager( 1065): ELAPSED_WAKEUP set : Alarm{13b0d85f type 2 when 180875 com.google.android.gms} when 180875
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1065): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6221 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6221): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6221): LgDataFeature() Constructor: none
D/LgDataFeature( 6221): LgDataFeature() Constructor Done, null
,I/Babel   ( 6221): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6221): MmsConfig.loadMmsSettings
I/Babel   ( 6221): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6221): MmsConfig.loadFromDatabase
,E/Babel   ( 6221): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6221): MmsConfig.loadFromResources
E/Babel   ( 6221): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6221): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6221): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6221): Unsupported mime audio/evrc
W/AudioCapabilities( 6221): Unsupported mime audio/qcelp
W/VideoCapabilities( 6221): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6221): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6221): Unsupported mime audio/qcelp
W/AudioCapabilities( 6221): Unsupported mime audio/evrc
W/VideoCapabilities( 6221): Unsupported mime video/x-ms-wmv
I/ActivityManager( 1065): Killing 5553:com.android.contacts/u0a19 (adj 15): empty #17
W/VideoCapabilities( 6221): Unsupported mime video/divx
W/VideoCapabilities( 6221): Unsupported mime video/divx311
,W/VideoCapabilities( 6221): Unsupported mime video/divx4
W/VideoCapabilities( 6221): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6221): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6221): Unsupported mime audio/eac3
W/AudioCapabilities( 6221): Unsupported mime audio/ac3
W/AudioCapabilities( 6221): Unsupported mime audio/g726
W/AudioCapabilities( 6221): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6221): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6221): Unsupported mime audio/adpcm
W/VideoCapabilities( 6221): Unsupported mime video/theora
,W/VideoCapabilities( 6221): Unsupported mime video/mjpg
W/libprocessgroup( 1065): failed to open /acct/uid_10019/pid_5553/cgroup.procs: No such file or directory
,V/AlarmManager( 1065): RTC_WAKEUP set : Alarm{e144d62 type 0 when 1456845425159 com.android.vending} when 1456845425159
,V/SIM_STK ( 1065): Menu title from STK is T-Mobile
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 197808843000; DSPS: 6622926; Offset : -4323403489
,D/Finsky  ( 5643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5643): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5643): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 217811127784; DSPS: 7278361; Offset : -4323408252
,V/AlarmManager( 1065): RTC_WAKEUP set : Alarm{374729d type 0 when 1456845457255 com.android.vending} when 1456845457255
,V/SIM_STK ( 1065): Menu title from STK is T-Mobile
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5643): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5643): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 237813676943; DSPS: 7933804; Offset : -4323392182
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1448): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1448): On Skip Timer : true
,D/WifiController( 1065): battery changed pluggedType: 2
,D/LEDHandler( 1946): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1946): Battery Level Remaining: 100%
D/LEDHandler( 1946): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1448): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1448): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1448): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 5915): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,V/AlarmManager( 1065): ELAPSED_WAKEUP set : Alarm{1005ea37 type 2 when 190057 android} when 190057
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 257816111623; DSPS: 8589244; Offset : -4323398830
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 277818118177; DSPS: 9244670; Offset : -4323406514
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 297820611973; DSPS: 9900112; Offset : -4323415160
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 317823258579; DSPS: 10555558; Offset : -4323392857
,I/LocationManagerService( 1065): remove 30342b6a
,D/LocationManagerService( 1065): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 1065): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1065): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService( 1065): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1065): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 337825520290; DSPS: 11210993; Offset : -4323420173
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 357827656637; DSPS: 11866423; Offset : -4323420031
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1448): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1448): On Skip Timer : true
,D/WifiController( 1065): battery changed pluggedType: 2
,D/LEDHandler( 1946): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1946): Battery Level Remaining: 100%
D/LEDHandler( 1946): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1448): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1448): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1448): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 5915): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1065): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1065): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1065): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1065): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1065): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1065): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5643): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5643): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5643): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1448): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do add job
D/LgeQuickCoverNotificationData( 1396): add : 2
D/LgeQuickCoverNotificationData( 1396): do add job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{bebb033 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 5643): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 377830858973; DSPS: 12521887; Offset : -4323391470
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 397833143237; DSPS: 13177322; Offset : -4323396103
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 417835612395; DSPS: 13832763; Offset : -4323398921
,D/PowerManagerServiceEx( 1065): acquireWakeLockInternal: lock=385494655, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1065
,V/AlarmManager( 1065): ELAPSED_WAKEUP set : Alarm{504a535 type 2 when 347917 com.google.android.gms} when 347917
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 24519(1117KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 43MB/65MB, paused 1.794ms total 132.002ms
,D/PowerManagerServiceEx( 1065): releaseWakeLockInternal: lock=385494655 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 437837882231; DSPS: 14488198; Offset : -4323417904
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 457840611860; DSPS: 15143647; Offset : -4323404391
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 477843056904; DSPS: 15799087; Offset : -4323400597
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 497845040281; DSPS: 16454512; Offset : -4323400966
,I/[SystemUI]LGPowerUI( 1448): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1448): On Skip Timer : true
,D/WifiController( 1065): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1448): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1448): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1946): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1946): Battery Level Remaining: 100%
D/LEDHandler( 1946): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1448): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5915): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4001): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 517847248607; DSPS: 17109944; Offset : -4323389776
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 537849060422; DSPS: 17765364; Offset : -4323409068
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 557851733645; DSPS: 18420811; Offset : -4323391004
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 577853993220; DSPS: 19076246; Offset : -4323420091
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 597856314462; DSPS: 19731682; Offset : -4323418185
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 617857755340; DSPS: 20387089; Offset : -4323411815
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 637859942467; DSPS: 21042520; Offset : -4323391228
,I/ActivityManager( 1065): Killing 5766:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1065): failed to open /acct/uid_10023/pid_5766/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 657862196783; DSPS: 21697954; Offset : -4323395239
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1065): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1065): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1065): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1065): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1065): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{bebb033 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5643): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5643): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5643): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5643): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 677864181359; DSPS: 22353379; Offset : -4323394384
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 697866134424; DSPS: 23008803; Offset : -4323394418
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 717868417541; DSPS: 23664238; Offset : -4323400041
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 737871138888; DSPS: 24319687; Offset : -4323394734
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 757873428047; DSPS: 24975122; Offset : -4323394444
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 777875813143; DSPS: 25630561; Offset : -4323420263
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 797878873135; DSPS: 26286021; Offset : -4323412054
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 817881250576; DSPS: 26941459; Offset : -4323414907
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 837883237756; DSPS: 27596884; Offset : -4323411526
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 857885514154; DSPS: 28252318; Offset : -4323393220
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 877887694146; DSPS: 28907750; Offset : -4323410415
,D/PowerManagerServiceEx( 1065): acquireWakeLockInternal: lock=385494655, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1065
,V/AlarmManager( 1065): ELAPSED_WAKEUP set : Alarm{162bab0f type 2 when 753824 com.google.android.gms} when 753824
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1065): releaseWakeLockInternal: lock=385494655 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 897889926899; DSPS: 29563183; Offset : -4323405655
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 917892131632; DSPS: 30218615; Offset : -4323398212
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 937894377770; DSPS: 30874049; Offset : -4323410297
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 957896715887; DSPS: 31529485; Offset : -4323391464
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1065): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1065): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1065): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1065): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1065): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5643): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5643): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5643): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{bebb033 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 5643): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 977899096348; DSPS: 32184923; Offset : -4323391635
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 997901926445; DSPS: 32840376; Offset : -4323399516
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1017904537635; DSPS: 33495822; Offset : -4323412734
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1037906775700; DSPS: 34151255; Offset : -4323402531
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1057908676474; DSPS: 34806677; Offset : -4323393768
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1077910714019; DSPS: 35462104; Offset : -4323401005
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1097912785365; DSPS: 36117532; Offset : -4323404932
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1117915068899; DSPS: 36772967; Offset : -4323410060
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1137917733787; DSPS: 37428414; Offset : -4323400201
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1157919786956; DSPS: 38083841; Offset : -4323391658
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1177922212939; DSPS: 38739281; Offset : -4323407107
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1197924649441; DSPS: 39394721; Offset : -4323412090
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
,I/[SystemUI]DateView( 1448): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1217927092923; DSPS: 40050161; Offset : -4323410014
,I/UsageStatsService( 1065): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1237929529426; DSPS: 40705601; Offset : -4323414918
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1257932826450; DSPS: 41361069; Offset : -4323413740
,I/[SystemUI]TimeTickManager( 1448): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1448): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1448): called onTimeUpdated()
I/[SystemUI]Clock( 1448): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
I/[SystemUI]DateView( 1448): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1448): handleTimeUpdate
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1065): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1065): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1065): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1065): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1065): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5643): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5643): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5643): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5643): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5643): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1065): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{bebb033 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1277935114828; DSPS: 42016504; Offset : -4323414102
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1065): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1065): tsOffsetIs: Apps: 1297937767997; DSPS: 42671951; Offset : -4323416118
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6511): 
D/AndroidRuntime( 6511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6511): CheckJNI is OFF
D/AndroidRuntime( 6511): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1065): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1065): Killing 6047:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1065): Skipping PackageSetting{21d654c0 com.example.hello/10319} due to missing metadata
I/WindowState( 1065): WIN DEATH: Window{317b6733 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1065): Client connection lost with reason: 4
D/InputDispatcher( 1065): Focus left window: Window{317b6733 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1065): Window went away: Window{317b6733 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1065):   Force finishing activity ActivityRecord{77879bc u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/ActivityManager( 1065): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1065):   Force finishing activity ActivityRecord{77879bc u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1065): Duplicate finish request for ActivityRecord{77879bc u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{1bd695fe co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1946): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1946): topRunningActivity=ActivityInfo{3c85715f co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2066): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2066): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1448): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1815): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2010): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2736): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/ActivityManager( 1065): Spurious death for ProcessRecord{18132a93 6047:com.test.thalitest/u0a311}, curProc for 6047: null
I/[LGHome]EVENT( 2066): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2066): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1901): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2066): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2736): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2066): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2066): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2066): [Launcher.java:1114:onPause()]onPause
I/InputReader( 1065): Reconfiguring input devices.  changes=0x00000010
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[SystemUI]QSlideListController( 1448): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 4267): Explicit concurrent mark sweep GC freed 16634(1036KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 426us total 96.175ms
W/System.err( 4226): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4226): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4226): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4226): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4226): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4226): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4226): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4226): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4226): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SplitUIManager( 1867): split_name #11 / not available #0
D/SplitUIService( 1867): removed split : 
I/ActivityManager( 1065): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6544 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/ActionManagerService( 1901): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2066): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2736): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1448): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1448): createShortcutInfo...
I/GBoardWebViewUtils( 2066): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2066): , create_time: 1430558575574
I/GBoardWebViewUtils( 2066): , expire_time: 0
I/GBoardWebViewUtils( 2066): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2066): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2066): , display: false
I/GBoardWebViewUtils( 2066): , animation: false }
I/GBoardWebViewUtils( 2066): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2066): , create_time: 1430558575600
I/GBoardWebViewUtils( 2066): , expire_time: 0
I/GBoardWebViewUtils( 2066): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2066): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2066): , display: false
I/GBoardWebViewUtils( 2066): , animation: false }
I/GBoardWebViewUtils( 2066): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2066): , create_time: 1455195785688
I/GBoardWebViewUtils( 2066): , expire_time: 0
I/GBoardWebViewUtils( 2066): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2066): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2066): , display: false
I/GBoardWebViewUtils( 2066): , animation: false }
D/KeyguardModel( 1448): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1448): createShortcutInfo...
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/WindowManager( 1065): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1065): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1065): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1065): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1065): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1065): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30170f51,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1065): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1448): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1448): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[SystemUI]NavigationThemeResource( 1448): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1448): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1448):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1448): , Keyguard show=false, IME shown=false, Panel expanded=false
D/WallpaperManager( 2066): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/InputDispatcher( 1065): Focus entered window: Window{e2f5cd6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
V/SIM_STK ( 1065): Menu title from STK is T-Mobile
D/KeyguardModel( 1448): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1448): createShortcutInfo...
I/[LGHome]EVENT( 2066): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2066): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/SplitUIManager( 1867): split_name #11 / not available #0
I/SplitUIService( 1867): split app #11
D/KeyguardModel( 1448): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1448): createShortcutInfo...
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1448): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1448): createShortcutInfo...
D/KeyguardModel( 1448): handleShortcutListChanged...
D/KeyguardModel( 1448): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1448): createShortcutInfo...
D/KeyguardModel( 1448): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1448): createShortcutInfo...
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1448): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1448): createShortcutInfo...
I/art     ( 1065): Explicit concurrent mark sweep GC freed 21194(1352KB) AllocSpace objects, 9(528KB) LOS objects, 33% free, 44MB/66MB, paused 2.305ms total 200.829ms
I/art     ( 1065): WaitForGcToComplete blocked for 200.144ms for cause Explicit
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1448): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1448): createShortcutInfo...
W/ResourceType( 1448): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1448): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1448): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1448): createShortcutInfo...
I/[LGHome]EVENT( 2066): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1448): handleShortcutListChanged...
I/[LGHome]EVENT( 2066): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2066): [setNavigationBarColor] color=0x 0
I/AppUp4:AppBoxCP( 6544): onCreate
D/[Concierge]WidgetView( 2066): notifyExtViewAvailable
W/AppUp4:DB( 6544):  [AppBoxDatabaseHelper] construct
D/InputMethodManagerService( 1065): setImestate : 0
W/InputMethodManagerService( 1065): Got RemoteException sending setActive(false) notification to pid 6047 uid 10311
I/AppUp4:DB( 6544):  setFingerPrint start
I/AppUp4:DB( 6544):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
D/administrator( 1065): Handling package changes for user 0
V/SIM_STK ( 1065): Menu title from STK is T-Mobile
I/AppUp4:DB( 6544):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6544):  SDK version = 21
I/AppUp4:DB( 6544):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6544): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 6544): added Exclude : com.test.thalitest
I/[LGHome]Launcher.Model( 2066): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/ActivityManager( 1065): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6564 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1065): Killing 5574:com.android.gallery3d/u0a27 (adj 15): empty #17
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 2066): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2066): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/NotificationService( 1065): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1065): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1065): Receieved: android.intent.action.PACKAGE_REMOVED
E/b       ( 1686): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2066): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2066): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2066): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2066): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2066): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/libprocessgroup( 1065): failed to open /acct/uid_10027/pid_5574/cgroup.procs: No such file or directory
D/[Concierge]Service( 2619): onStartCommand(). Type : 8
D/[Concierge]Service( 2619): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2619): Update widget ID : 11
D/[Concierge]WidgetView( 2066): change position of spinner
D/TaskPersister( 1065): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1065): Timeline: Activity_windows_visible id: ActivityRecord{1d32425f u0 com.lge.launcher2/.Launcher t3} time:1307135
I/[Concierge]WidgetView( 2066): initWebView(). Time : 1456846546582
D/[Concierge]Service( 2619): onStartCommand(). Type : 0
W/ResourcesManager( 6564): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6564): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6564): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6564): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6564): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2066): Return exist ConciergeWebView. Reuse : 226292711
D/[Concierge]WidgetView( 2066): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2066): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2066): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@a315b9b
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2066): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2066): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2066): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/art     ( 1065): Explicit concurrent mark sweep GC freed 7764(440KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 44MB/66MB, paused 1.744ms total 230.564ms
W/[Concierge]WidgetView( 2066): Widget kill message received. Destory myself. My : 1456845267562, New one : 1456846546582
D/[Concierge]WidgetView( 2066): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2066): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 6564): BUILD Country: EU
I/SystemConfig( 6564): BUILD Operator: OPEN
I/[LgeWidgetLib]LgeAppWidgetHostView( 2066): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1065): Killing 5820:com.google.android.apps.docs/u0a61 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2066): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2066): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2066): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 6511): Shutting down VM
W/ResourceType( 1065): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/Timeline( 2066): Timeline: Activity_idle id: android.os.BinderProxy@1dd7534c time:1307274
W/libprocessgroup( 1065): failed to open /acct/uid_10061/pid_5820/cgroup.procs: No such file or directory
I/SystemConfig( 6564): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6564): existFile = false
I/SystemConfig( 6564): canReadFile = false
I/SystemConfig( 6564): systemFeature RCS result false
D/SystemConfig( 6564): refreshRcsSupport() :false
I/[LGHome]EVENT( 2066): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/VoicemailCleanupService( 2190): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1065): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6586 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 6586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6586): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6586): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6586): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2066): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/LGEmail ( 6586): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6586): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/GBoardtInterface( 2066): onReloaded()
I/GBoardWebViewClient( 2066): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2736): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2736): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1901): notifyUserLog: 1000001
V/BoardContentProvider( 2736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2736): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2736): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2736): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2736): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2066): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2066): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2066): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2066): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
W/ResourceType( 6586): No package identifier when getting value for resource number 0x00000000
D/GBoardUriUtils( 2066): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2066): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LgDataFeature( 6586): LgDataFeature() Constructor: none
D/LgDataFeature( 6586): LgDataFeature() Constructor Done, null
I/PackageChangeReceiver( 6586): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1065): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6618 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager( 1065): Killing 5618:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1065): failed to open /acct/uid_10097/pid_5618/cgroup.procs: No such file or directory
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
