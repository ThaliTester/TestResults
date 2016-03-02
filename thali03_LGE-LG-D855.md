#### Test 613623666a5dbc7_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/art     ( 1028): Explicit concurrent mark sweep GC freed 16038(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.736ms total 142.480ms
I/art     ( 2135): Explicit concurrent mark sweep GC freed 18131(1001KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.161ms total 33.037ms
,D/AndroidRuntime( 6120): 
D/AndroidRuntime( 6120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6120): CheckJNI is OFF
D/AndroidRuntime( 6120): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1028): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1964): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1028): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{27ff5e56 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{27ff5e56 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1028): AppWindowTokenEx init.. 
E/GBMv2   (  338): DFP En is all cleared set to be enabled
I/ActivityManager( 1028): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6141 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1028): Focus left window: Window{52536c0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2082): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 6120): Shutting down VM
V/ActivityManager( 1028): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{3efd7924 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{22adbc8d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6141): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/WebViewFactory( 6141): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6141): Loading: webviewchromium
I/LibraryLoader( 6141): Time to load native libraries: 3 ms (timestamps 6160-6163)
I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6141): Binding Chromium to main looper Looper (main, tid 1) {5addfbe}
I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
I/chromium( 6141): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6141): Initializing chromium process, renderers=0
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6141): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  314): registerClient() client 0xb152a200, uid 10311
,W/chromium( 6141): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6141): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 6141): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1028): Message: 20
D/BluetoothManagerService( 1028): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26791830:true
,D/BluetoothAdapter( 6141): 807950367: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6141): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6141): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6141): Build Date: 12/12/14 금
I/Adreno-EGL( 6141): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6141): Remote Branch: 
I/Adreno-EGL( 6141): Local Patches: 
I/Adreno-EGL( 6141): Reconstruct Branch: 
,W/chromium( 6141): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6141): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6141): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 6141): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6141): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6141): [setNavigationBarColor2] color=0x fff5f5f5
,D/SystemWebViewEngine( 6141): CordovaWebView is running on device made by: LGE
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6141): Render dirty regions requested: true
I/OpenGLRenderer( 6141): Initialized EGL, version 1.4
D/OpenGLRenderer( 6141): Enabling debug mode 0
,W/ActivityManager( 1028): Activity pause timeout for ActivityRecord{22fd8ed7 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6141): Validating map...
,D/SplitWindow( 1028): check instance of lgWin Window{213b9eea u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WindowManager( 1028): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework]( 1028): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,I/[SystemUI]NavigationThemeResource( 1461): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1028): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1028): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1028): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15fba428,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6141): LgDataFeature() Constructor: none
,D/InputDispatcher( 1028): Focus entered window: Window{213b9eea u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6141): LgDataFeature() Constructor Done, null
,D/InputMethodManagerService( 1028): setImestate : 0
,I/ActivityManager( 1028): Displayed com.test.thalitest/.MainActivity: +614ms (total +709ms)
I/Timeline( 1028): Timeline: Activity_windows_visible id: ActivityRecord{22fd8ed7 u0 com.test.thalitest/.MainActivity t4} time:96596
,W/IInputConnectionWrapper( 6141): showStatusIcon on inactive InputConnection
I/Timeline( 6141): Timeline: Activity_idle id: android.os.BinderProxy@2466a97a time:96603
W/IInputConnectionWrapper( 6141): getTextBeforeCursor on inactive InputConnection
E/b       ( 1691): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6141): getTextAfterCursor on inactive InputConnection
,D/JsMessageQueue( 6141): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6141): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6141): 
,I/chromium( 6141): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6141): 
,D/jxcore_app_log( 6141): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435224192
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6141): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f451ff added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@167c652a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6141): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1028): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6141): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6141): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6141): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6141): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6141): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 6141): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 97796695434; DSPS: 3345518; Offset : -4312579545
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
E/GBMv2   (  338): Set value is all cleared set the max
I/GBMv2   (  338): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6141): Initializing JXcore engine
W/jxcore-log( 6141): JXcore engine is ready
,W/Thread-705( 6210): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7520]" dev="sockfs" ino=7520 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-705( 6210): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-705( 6210): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[8577]" dev="sockfs" ino=8577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-705( 6210): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-705( 6210): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28623]" dev="sockfs" ino=28623 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6141): Starting JXcore engine
,W/jxcore-log( 6141): Platform android
W/jxcore-log( 6141): 
W/jxcore-log( 6141): Process ARCH arm
W/jxcore-log( 6141): 
,I/jxcore-log( 6141): JXcore Cordova bridge is ready!
I/jxcore-log( 6141): 
,W/jxcore-log( 6141): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6141): execute: REQUEST_ACCESS_COARSE_LOCATION
I/rmt_storage(  307): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  307): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  307): wakelock acquired: 1, error no: 42
,I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  307): 
,I/rmt_storage(  307): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,E/Diag_Lib(  897): [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6141): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 6141): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 6141): BLE multiple advertisement supported
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): My device name is: LGE-LG-D855
I/jxcore-log( 6141): 
,I/MusicWidget( 2672): mDelayedStopHandler : unbind
,I/MusicBrowser( 2229): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2229): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2229): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2229): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2229): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2229): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1028):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3bb581a5com.lge.music.MediaPlaybackService$5@2466a97a
,D/MusicBrowser( 2229): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2f84573b
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2229): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2229): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2229): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2229): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2229): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2229): reset
V/MediaPlayer[Native]( 2229): setListener
V/MediaPlayer[Native]( 2229): disconnect
V/MediaPlayer[Native]( 2229): destructor
,V/AudioFlinger(  314): releasing 13 from 2229 for -1
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
V/MediaPlayer[Native]( 2229): disconnect
D/MusicBrowser( 2229): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2229): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2229): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2229): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2229): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2229): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2229): [SmartShareManagerClient] unregisterListener: 364217643
W/SmartShareClient( 2229): [SmartShareManagerClient] unregisterListener invalid listener: 364217643
,I/SmartShareClient( 2229): [SmartShareManagerClient] terminate service: 2229/MediaPlaybackService/717379193
E/HomeCloudIF( 2229): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2229): [SmartShareManagerClient] unbindService context:android.app.Application@371efd88
V/CloudHub( 2229): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2229): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2229): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2229): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,I/ActivityManager( 1028): Killing 5619:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/CloudHub( 2229): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
W/libprocessgroup( 1028): failed to open /acct/uid_10011/pid_5619/cgroup.procs: No such file or directory
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6141): 
I/jxcore-log( 6141): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6141): 
I/io.jxcore.node.ConnectivityInfo( 6141): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6141):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6141):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6141):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 6141):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6141):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 6141):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 6141):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 6141):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6141): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
I/jxcore-log( 6141): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6141): 
I/jxcore-log( 6141): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6141): 
V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{3cbb44b7 type 2 when 103889 com.google.android.gms} when 103889
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{dcf5b8d type 0 when 1456906105411 com.android.vending} when 1456906105411
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ContextImpl( 4268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1028): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6219 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6219): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
D/LgDataFeature( 6219): LgDataFeature() Constructor: none
D/LgDataFeature( 6219): LgDataFeature() Constructor Done, null
,I/Babel   ( 6219): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6219): MmsConfig.loadMmsSettings
I/Babel   ( 6219): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,I/Babel   ( 6219): MmsConfig.loadFromDatabase
E/Babel   ( 6219): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6219): MmsConfig.loadFromResources
W/Settings( 6219): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 6219): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6219): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6219): Unsupported mime audio/evrc
,W/AudioCapabilities( 6219): Unsupported mime audio/qcelp
W/VideoCapabilities( 6219): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6219): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6219): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6219): Unsupported mime audio/evrc
W/VideoCapabilities( 6219): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6219): Unsupported mime video/divx
,W/VideoCapabilities( 6219): Unsupported mime video/divx311
W/VideoCapabilities( 6219): Unsupported mime video/divx4
,W/VideoCapabilities( 6219): Unsupported mime video/mp4v-esdp
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VideoCapabilities( 6219): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6219): Unsupported mime audio/eac3
W/AudioCapabilities( 6219): Unsupported mime audio/ac3
W/AudioCapabilities( 6219): Unsupported mime audio/g726
,W/AudioCapabilities( 6219): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6219): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6219): Unsupported mime audio/adpcm
W/VideoCapabilities( 6219): Unsupported mime video/theora
W/VideoCapabilities( 6219): Unsupported mime video/mjpg
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1028): Killing 5649:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1028): failed to open /acct/uid_10019/pid_5649/cgroup.procs: No such file or directory
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 6141): 
,I/CloudHub( 2229): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19985
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): Unit Test app is loaded
I/jxcore-log( 6141): 
,I/chromium( 6141): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
I/jxcore-log( 6141): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 6141): 
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 117798512718; DSPS: 4000938; Offset : -4312593680
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{37d5783e type 0 when 1456906126005 com.android.vending} when 1456906126005
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2229): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2229): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 137801177138; DSPS: 4656385; Offset : -4312584263
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 157803292182; DSPS: 5311815; Offset : -4312605476
,D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{35051a69 type 0 when 1456906149524 com.android.vending} when 1456906149524
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 4.
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 177805438998; DSPS: 5967245; Offset : -4312594864
,V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{c31b523 type 2 when 180390 com.google.android.gms} when 180390
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{215c6fd9 type 0 when 1456906180878 com.android.vending} when 1456906180878
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1028): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/MainApplication( 5963): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 197807533938; DSPS: 6622674; Offset : -4312605585
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{20432b50 type 0 when 1456906202526 com.android.vending} when 1456906202526
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5754): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 217809585647; DSPS: 7278101; Offset : -4312598450
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 237812078142; DSPS: 7933542; Offset : -4312578034
,V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{a8b4db2 type 2 when 190241 android} when 190241
,V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{38a88103 type 2 when 197064 com.google.android.gms} when 197064
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 257814135269; DSPS: 8588970; Offset : -4312596129
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 277815820262; DSPS: 9244385; Offset : -4312589603
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/WifiController( 1028): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5963): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 297817847337; DSPS: 9899812; Offset : -4312607284
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 317819902902; DSPS: 10555239; Offset : -4312596188
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,I/LocationManagerService( 1028): remove 1cefbe33
,D/LocationManagerService( 1028): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 1028): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1028): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService( 1028): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1028): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 337822599197; DSPS: 11210687; Offset : -4312585544
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 357824692471; DSPS: 11866116; Offset : -4312597931
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 259, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 259
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1028): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 5963): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1409): onNotificationPosted
D/SmartCoverUpdateMonitor( 1409): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1409): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1409): handleNotificationPosted(true)
D/QuickCircle( 1409): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1409): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post do just update job
D/LgeQuickCoverNotificationData( 1409): showAll3
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1409): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1409): updateNotificationData: count=3
D/QuickStatusbarLayout( 1409): Notification difference=198
D/QuickStatusbarLayout( 1409): child = android.widget.LinearLayout{2a4bd6e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5754): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5754): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5754): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5754): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 377826523400; DSPS: 12521536; Offset : -4312598057
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 397828635372; DSPS: 13176965; Offset : -4312591849
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 417829984270; DSPS: 13832369; Offset : -4312585829
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 437832079837; DSPS: 14487798; Offset : -4312595949
,D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{2a56694f type 2 when 428709 com.google.android.gms} when 428709
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,I/art     ( 1028): Explicit concurrent mark sweep GC freed 23862(1086KB) AllocSpace objects, 3(182KB) LOS objects, 33% free, 43MB/65MB, paused 2.273ms total 141.980ms
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 457836194620; DSPS: 15143293; Offset : -4312600961
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 477838233362; DSPS: 15798720; Offset : -4312606793
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 497840890803; DSPS: 16454167; Offset : -4312604433
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 517843357931; DSPS: 17109607; Offset : -4312578815
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 537845491725; DSPS: 17765037; Offset : -4312581227
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 557847315311; DSPS: 18420457; Offset : -4312588668
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/WifiController( 1028): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4055): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/MainApplication( 5963): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 577848936657; DSPS: 19075870; Offset : -4312584650
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 597851031390; DSPS: 19731299; Offset : -4312595682
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 617852688204; DSPS: 20386713; Offset : -4312586765
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 637854195905; DSPS: 21042122; Offset : -4312574529
,I/ActivityManager( 1028): Killing 5872:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1028): failed to open /acct/uid_10023/pid_5872/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 657860490065; DSPS: 21697689; Offset : -4312597378
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1409): onNotificationPosted
D/SmartCoverUpdateMonitor( 1409): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1409): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1409): handleNotificationPosted(true)
D/QuickCircle( 1409): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1409): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post do just update job
D/LgeQuickCoverNotificationData( 1409): showAll3
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1409): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1409): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 5754): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5754): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5754): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5754): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1409): Notification difference=198
D/QuickStatusbarLayout( 1409): child = android.widget.LinearLayout{2a4bd6e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 677862295942; DSPS: 22353108; Offset : -4312592169
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 697866364841; DSPS: 23008601; Offset : -4312582081
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 717868222646; DSPS: 23664022; Offset : -4312585978
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 737870156597; DSPS: 24319446; Offset : -4312605048
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 757871526953; DSPS: 24974850; Offset : -4312577440
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 777873619811; DSPS: 25630279; Offset : -4312590399
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 797875530740; DSPS: 26285702; Offset : -4312601895
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 817877371618; DSPS: 26941122; Offset : -4312592281
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 837879506558; DSPS: 27596552; Offset : -4312593466
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 857882247436; DSPS: 28252002; Offset : -4312599170
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 877883804668; DSPS: 28907413; Offset : -4312598283
,D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,D/Finsky  ( 5754): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{14f1685e type 0 when 1456906718341 com.android.vending} when 1456906718341
V/AlarmManager( 1028): ELAPSED_WAKEUP set : Alarm{f4a443f type 2 when 793388 com.google.android.gms} when 793388
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,W/Finsky  ( 5754): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5754): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5754): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5754): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 5754): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5754): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
D/DeviceConnectionService( 1833): client connected with version: 7571000
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 897885825285; DSPS: 29562839; Offset : -4312591930
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{aee55e9 type 0 when 1456906903443 com.android.vending} when 1456906903443
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 1.
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 917887942569; DSPS: 30218268; Offset : -4312580333
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{2a0153a0 type 0 when 1456906924648 com.android.vending} when 1456906924648
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 937889334801; DSPS: 30873674; Offset : -4312591884
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 957891963388; DSPS: 31529120; Offset : -4312587834
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{f0cdc93 type 0 when 1456906946999 com.android.vending} when 1456906946999
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 31757(1837KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 1.551ms total 48.036ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1409): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1409): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1409): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1409): handleNotificationPosted(true)
D/QuickCircle( 1409): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1409): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post do just update job
D/LgeQuickCoverNotificationData( 1409): showAll3
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1409): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1409): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5754): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5754): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5754): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5754): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1409): Notification difference=198
D/QuickStatusbarLayout( 1409): child = android.widget.LinearLayout{2a4bd6e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 977893841401; DSPS: 32184542; Offset : -4312601937
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{3bf77dd7 type 0 when 1456906979188 com.android.vending} when 1456906979188
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 997895608164; DSPS: 32839960; Offset : -4312605062
,D/PowerManagerServiceEx( 1028): acquireWakeLockInternal: lock=760434348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{5f31406 type 0 when 1456907000089 com.android.vending} when 1456907000089
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9,
,D/PowerManagerServiceEx( 1028): releaseWakeLockInternal: lock=760434348 [*alarm*], flags=0x0
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1028): Explicit concurrent mark sweep GC freed 23986(986KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 3.002ms total 144.708ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1017897721437; DSPS: 33495389; Offset : -4312597607
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1037899804086; DSPS: 34150817; Offset : -4312590128
,V/AlarmManager( 1028): RTC_WAKEUP set : Alarm{202f7251 type 0 when 1456907030327 com.android.vending} when 1456907030327
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5754): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5754): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5754): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1057901823610; DSPS: 34806243; Offset : -4312584764
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1077903429070; DSPS: 35461656; Offset : -4312596735
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1097905561928; DSPS: 36117086; Offset : -4312600134
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1117907053326; DSPS: 36772495; Offset : -4312603889
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1137909087380; DSPS: 37427921; Offset : -4312584177
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1157911238416; DSPS: 38083352; Offset : -4312599967
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1177913191741; DSPS: 38738776; Offset : -4312599636
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1197914972932; DSPS: 39394194; Offset : -4312588465
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1217917071309; DSPS: 40049623; Offset : -4312595776
,I/UsageStatsService( 1028): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1237918892603; DSPS: 40705043; Offset : -4312605562
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1257921555044; DSPS: 41360490; Offset : -4312598229
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1409): onNotificationPosted
D/SmartCoverUpdateMonitor( 1409): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1409): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1409): handleNotificationPosted(true)
D/QuickCircle( 1409): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1409): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): post do just update job
D/LgeQuickCoverNotificationData( 1409): showAll3
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1409): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1409): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1409): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1409): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1409): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 5754): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5754): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5754): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5754): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 5754): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/QuickStatusbarLayout( 1409): Notification difference=198
,D/QuickStatusbarLayout( 1409): child = android.widget.LinearLayout{2a4bd6e7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1277923674984; DSPS: 42015919; Offset : -4312583923
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 1297925660237; DSPS: 42671344; Offset : -4312582469
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6602): 
D/AndroidRuntime( 6602): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6602): CheckJNI is OFF
D/AndroidRuntime( 6602): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1028): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1028): Killing 6141:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1028): WIN DEATH: Window{213b9eea u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1028): Skipping PackageSetting{2d279664 com.example.hello/10319} due to missing metadata
D/WifiService( 1028): Client connection lost with reason: 4
D/InputDispatcher( 1028): Focus left window: Window{213b9eea u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1028): Window went away: Window{213b9eea u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1028):   Force finishing activity ActivityRecord{22fd8ed7 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  338): DFP En is all cleared set to be enabled
W/ActivityManager( 1028): Spurious death for ProcessRecord{222a16ec 6141:com.test.thalitest/u0a311}, curProc for 6141: null
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{157a6e42 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{3bc53e53 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1028): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1028): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2043): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2747): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1833): Ignoring removeGeofence because network location is disabled.
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1919): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/PostponalbeReceiver( 5272): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
D/ActionManagerService( 1919): notifyUserLog: 1000004
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/LIA_Informant_ActionManagerMessageHandler( 2747): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
W/System.err( 4268): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4268): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4268): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4268): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4268): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4268): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4268): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4268): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4268): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4318): Explicit concurrent mark sweep GC freed 14843(857KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 383us total 103.877ms
I/ActivityManager( 1028): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6634 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/KeyguardModel( 1461): handleShortcutListChanged...
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
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2082): , create_time: 1455195785688
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/WindowManager( 1028): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1028): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]NavigationThemeResource( 1461): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/PhoneWindowManagerEx( 1028): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1028): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1028): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15fba428,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
D/InputDispatcher( 1028): Focus entered window: Window{52536c0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/SplitUIManager( 1885): split_name #11 / not available #0
D/SplitUIService( 1885): removed split : 
D/KeyguardModel( 1461): handleShortcutListChanged...
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
I/art     ( 1028): Explicit concurrent mark sweep GC freed 15495(1056KB) AllocSpace objects, 7(240KB) LOS objects, 33% free, 44MB/66MB, paused 2.005ms total 186.493ms
I/art     ( 1028): WaitForGcToComplete blocked for 59.630ms for cause Explicit
I/AppUp4:AppBoxCP( 6634): onCreate
W/AppUp4:DB( 6634):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6634):  setFingerPrint start
I/AppUp4:DB( 6634):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
D/SplitUIManager( 1885): split_name #11 / not available #0
I/SplitUIService( 1885): split app #11
I/AppUp4:DB( 6634):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6634):  SDK version = 21
I/AppUp4:DB( 6634):  beforefinger == newfinger no write in DB
D/administrator( 1028): Handling package changes for user 0
D/AppUp4:AppBoxApplication( 6634): AppBoxApplication onCreate()
I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2082): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2082): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2082): notifyExtViewAvailable
D/AppUp4:PreloadHelper( 6634): added Exclude : com.test.thalitest
I/ActivityManager( 1028): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6656 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1028): Killing 5669:com.android.gallery3d/u0a27 (adj 15): empty #17
I/art     ( 1028): Explicit concurrent mark sweep GC freed 9436(630KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 6.176ms total 134.703ms
W/libprocessgroup( 1028): failed to open /acct/uid_10027/pid_5669/cgroup.procs: No such file or directory
I/NotificationService( 1028): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1028): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1028): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1028): removeObsoleteFile: deleting file=4_task.xml
D/InputMethodManagerService( 1028): setImestate : 0
W/InputMethodManagerService( 1028): Got RemoteException sending setActive(false) notification to pid 6141 uid 10311
W/ResourcesManager( 6656): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6656): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6656): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6656): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6656): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6656): BUILD Country: EU
I/SystemConfig( 6656): BUILD Operator: OPEN
D/AndroidRuntime( 6602): Shutting down VM
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager( 1028): Killing 5900:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/ResourcesManager( 1028): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1028): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/IInputConnectionWrapper( 2082): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1691): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2082): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/libprocessgroup( 1028): failed to open /acct/uid_10061/pid_5900/cgroup.procs: No such file or directory
D/[Concierge]Service( 2620): onStartCommand(). Type : 8
D/[Concierge]Service( 2620): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2620): Update widget ID : 11
I/SystemConfig( 6656): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/Timeline( 1028): Timeline: Activity_windows_visible id: ActivityRecord{543bf53 u0 com.lge.launcher2/.Launcher t3} time:1307615
I/SystemConfig( 6656): existFile = false
I/SystemConfig( 6656): canReadFile = false
I/SystemConfig( 6656): systemFeature RCS result false
D/SystemConfig( 6656): refreshRcsSupport() :false
D/[Concierge]WidgetView( 2082): change position of spinner
D/VoicemailCleanupService( 2156): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1028): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6678 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/[Concierge]Service( 2620): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1456907303390
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 292342462
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2d76c548
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1456906023902, New one : 1456907303390
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
W/ResourcesManager( 6678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/LGEmail ( 6678): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6678): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/ResourceType( 6678): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@8412d30 time:1307813
D/LgDataFeature( 6678): LgDataFeature() Constructor: none
D/LgDataFeature( 6678): LgDataFeature() Constructor Done, null
I/PackageChangeReceiver( 6678): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
