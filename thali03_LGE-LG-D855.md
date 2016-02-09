#### Test 5841644866d9c0e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2669): mDelayedStopHandler : unbind
,I/MusicBrowser( 2236): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2236): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2236): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2236): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1037):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@5ef99e6com.lge.music.MediaPlaybackService$5@35cccb27
D/MusicBrowser( 2236): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1a1ff7a4
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2236): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2236): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2236): reset
V/MediaPlayer[Native]( 2236): setListener
V/MediaPlayer[Native]( 2236): disconnect
V/MediaPlayer[Native]( 2236): destructor
V/AudioFlinger(  325): releasing 13 from 2236 for -1
V/AudioFlinger(  325):  decremented refcount to 0
V/AudioFlinger(  325): purging stale effects
V/MediaPlayer[Native]( 2236): disconnect
D/MusicBrowser( 2236): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2236): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2236): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2236): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener: 356684244
W/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener invalid listener: 356684244
I/SmartShareClient( 2236): [SmartShareManagerClient] terminate service: 2236/MediaPlaybackService/1039097450
E/HomeCloudIF( 2236): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2236): [SmartShareManagerClient] unbindService context:android.app.Application@33bedf7d
V/CloudHub( 2236): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2236): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1037): Killing 5613:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29963
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_5613/cgroup.procs: No such file or directory
D/AndroidRuntime( 6342): 
D/AndroidRuntime( 6342): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6342): CheckJNI is OFF
D/AndroidRuntime( 6342): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1979): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{22b8c774 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{22b8c774 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6371 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6342): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{178974eb co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{3fe89248 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 26575(1349KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.610ms total 113.541ms
,D/ContextHelper( 6371): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/WebViewFactory( 6371): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6371): Loading: webviewchromium
I/LibraryLoader( 6371): Time to load native libraries: 3 ms (timestamps 6273-6276)
I/LibraryLoader( 6371): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6371): Binding Chromium to main looper Looper (main, tid 1) {3dabaf5b}
I/LibraryLoader( 6371): Expected native library version number "",actual native library version number ""
I/chromium( 6371): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6371): Initializing chromium process, renderers=0
W/art     ( 6371): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6371): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  325): registerClient() client 0xb54eaf20, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1751885e:true
W/chromium( 6371): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6371): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6371): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/Adreno-EGL( 6371): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6371): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6371): Build Date: 12/12/14 금
I/Adreno-EGL( 6371): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6371): Remote Branch: 
I/Adreno-EGL( 6371): Local Patches: 
I/Adreno-EGL( 6371): Reconstruct Branch: 
,W/chromium( 6371): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6371): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6371): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6371): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6371): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6371): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6371): [setNavigationBarColor2] color=0x fff5f5f5
,W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{d2a749d u0 com.test.thalitest/.MainActivity t4}
,D/SystemWebViewEngine( 6371): CordovaWebView is running on device made by: LGE
W/art     ( 6371): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6371): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6371): Render dirty regions requested: true
I/OpenGLRenderer( 6371): Initialized EGL, version 1.4
D/OpenGLRenderer( 6371): Enabling debug mode 0
D/Atlas   ( 6371): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{378c8928 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6371): LgDataFeature() Constructor: none
D/LgDataFeature( 6371): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +659ms (total +759ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{d2a749d u0 com.test.thalitest/.MainActivity t4} time:106656
,I/Timeline( 6371): Timeline: Activity_idle id: android.os.BinderProxy@5ef99e6 time:106660
I/chromium( 6371): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6371): 
,D/JsMessageQueue( 6371): Set native->JS mode to OnlineEventsBridgeMode
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,E/GBMv2   (  343): Set value is all cleared set the max
,I/GBMv2   (  343): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6371): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435216512
,I/chromium( 6371): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6371): 
,I/chromium( 6371): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6371): Initializing JXcore engine
W/jxcore-log( 6371): JXcore engine is ready
,W/Thread-724( 6422): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7441]" dev="sockfs" ino=7441 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-724( 6422): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-724( 6422): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10398]" dev="sockfs" ino=10398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-724( 6422): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-724( 6422): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[31102]" dev="sockfs" ino=31102 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6371): Starting JXcore engine
,W/jxcore-log( 6371): Platform android
W/jxcore-log( 6371): 
,W/jxcore-log( 6371): Process ARCH arm
W/jxcore-log( 6371): 
,I/jxcore-log( 6371): JXcore Cordova bridge is ready!
I/jxcore-log( 6371): 
W/jxcore-log( 6371): JXcore engine is started
,I/jxcore-log( 6371): Toggling radios to true
I/jxcore-log( 6371): 
,D/BluetoothAdapter( 6371): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6371, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1037): setWifiEnabled: true pid=6371, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6371, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1037): setLastSelectedConfiguration -1
E/WifiNative: ( 1037): [108,910,469 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=6371, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6371): Radios toggled
I/jxcore-log( 6371): 
I/jxcore-log( 6371): My device name is: LGE-LG-D855
I/jxcore-log( 6371): 
I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
D/Tethering( 1037): InitialState.processMessage what=4
,D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiNative: ( 1037): [108,961,311 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
,I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=108982
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=108983  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6426 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=109007  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109013  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109015  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6426): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6426): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6426): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6426): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6426): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6426): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6426): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 6426): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6455 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 5635:com.android.contacts/u0a19 (adj 15): empty #17
I/art     (  361): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 389us total 19.164ms
,I/art     (  361): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 15.186ms
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 12.960ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_5635/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6426): LgDataFeature() Constructor: none
D/LgDataFeature( 6426): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6455): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6455): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6455): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6219): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6219): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1037): Killing 6049:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6049/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2677): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3247 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3247 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3247 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3247 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=111050  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=111056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
,D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2677): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=111164  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=111164  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111165
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111165
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111165
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111165
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111165
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=111166  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6426): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6426): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6426): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=111168  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2677): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2677): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed, [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111175  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=111175  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111176
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111176
D/WifiNative-wlan0( 1037): doString: [STATUS]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6426): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6426): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6426): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6426): [AUTORUN] setTetherStatus() : status=false
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  321): Setting iface cfg
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1037): StoppedState
E/WifiStateMachine( 1037): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=111223  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=111223  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=111223  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
,V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
,D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39e3bb88 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39e3bb88 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{d23d146 type 0 when 1455019835935 com.android.vending} when 1455019835935
,V/QRemote ( 6219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6219): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8008
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6515): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6515): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6515): version 5.5.6 starting
E/dhcpcd  ( 6515): get_duid: m
,D/dhcpcd  ( 6515): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6515): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6515): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6515): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6515): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6515): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6515): wlan0: sending REQUEST (xid 0x8f4a0cfb), next in 4.78 seconds
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5739): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5739): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5739): [1] 5.onFinished: Scheduling replication attempt 2.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/dhcpcd  ( 6515): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6515): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6515): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6515): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6515): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6515): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6515): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6515): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6515): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2677): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 100
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1979): handleWifiStateChangedEvent: 1
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1480): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 100
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1037): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 28
,D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): Sending msg: 5 arg1:0 arg2:1
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  321): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  321): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1037): requestTime failed
D/LocSvc_java( 1037): Sending msg: 10 arg1:0 arg2:1
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
W/dsqn    ( 6567): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6567): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
,E/DSQN    ( 6567): DSQN ssw
D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
I/QRemote ( 6219): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6455): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6455): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/LGDataListener(  321): argv[0]=dsqncommand
D/LGDataListener(  321): argv[1]=wlan0
D/LGDataListener(  321): argv[2]=1
D/LGDataListener(  321): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6219): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6219): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6219): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6455): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6455): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6426): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:10:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455019838066], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455019838046]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524290
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WiFiOffLoadBroadcast( 6426): MCCMNC not supported: null
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6219): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6219): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6219): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6219): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6371): 
I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6371): 
,I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19953
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5983): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5346): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  321): res_queryN name = 2.android.pool.ntp.org succeed
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6592 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlarmManagerService( 1037): Setting time of day to sec=1455019840
W/AlarmManagerService( 1037): Unable to set rtc to 1455019840: Invalid argument
I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6614 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
I/SecureClockService( 1979): Intent.ACTION_TIME_CHANGED 
,I/[SystemUI]Clock( 1480): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1480): time changed, timezoneChanged : false
W/ActivityManager( 1037): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
D/LIA_Informant_Tips_DateChangeManager( 2742): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2742): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-09 13:10:40...... Request
I/LIA_Informant_Tips_LogTracer( 2742): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 170, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2742): DateInfo : SmartTips Total Working Day Count = 170
D/LIA_Informant_Tips_DateChangeManager( 2742): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2742): DateInfo : Last Date Check Time = 2016-02-09 13:10:40
I/CalendarProvider2( 5513): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5513): Scheduling check of next Alarm
I/[LGHome]LGDateChangeReceiver( 2087): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2087): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
,I/[LGHome]LGCalendarIcon( 2087): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2619): onStartCommand(). Type : 9
I/AppUp4:AppBoxCP( 6592): onCreate
W/AppUp4:DB( 6592):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6592):  setFingerPrint start
I/AppUp4:DB( 6592):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6592):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6592):  SDK version = 21
I/AppUp4:DB( 6592):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6592): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6592): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6592): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6592): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6592): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6592): onReceive
,D/LgDataFeature( 6592): LgDataFeature() Constructor: none
D/LgDataFeature( 6592): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6592): Context : android.app.ReceiverRestrictedContext@ce993f8
D/AppUp4:CustFacade( 6592): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6592): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6592): begin check event
I/AppUp4:CustModeStarterReceiver( 6592): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6592): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6592): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6592): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6592): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1037): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6634 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LGDMClient( 4128): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4128): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 4128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3330): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3330): DownloadService onCreate
D/LGDMClient( 4128): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3330): in removeSpuriousFiles
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@13e8cc17 on behalf of 3330
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3330): in trimDatabase
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@19181804 on behalf of 3330
D/LGDMClient( 4128): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4128): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6657 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/GpsLocationProvider( 1037): No APN found to select.
I/LGDMClient( 4128): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3330): DownloadService onStartCommand
,V/DownloadManager( 3330): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@10a412b3 on behalf of 3330
I/ReaderUtils( 6614): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/ContextImpl( 4128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4128): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4128): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4128): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3330): processing inserted download 1
V/DownloadManager( 3330): processing inserted download 4
V/DownloadManager( 3330): processing inserted download 7
,I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
V/DownloadManager( 3330): processing inserted download 8
I/Thermal-Lib( 3106): Thermal-Lib-Client: Client request sent
V/DownloadManager( 3330): processing inserted download 9
V/DownloadManager( 3330): processing inserted download 10
W/ResourcesManager( 6657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3330): processing inserted download 16
V/DownloadManager( 3330): processing inserted download 17
,V/DownloadManager( 3330): processing inserted download 18
V/DownloadManager( 3330): processing inserted download 21
V/DownloadManager( 3330): processing inserted download 22
,W/DriveInitializer( 2353): Background init thread started
W/GAV2    ( 6614): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
V/DownloadManager( 3330): DownloadService onDestroy
I/BooksApp( 6614): Created application version: 3.2.35 (30235)
I/LGEmail ( 6657): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/DriveInitializer( 2353): Background init thread ended
D/LGEmail ( 6657): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6657): No package identifier when getting value for resource number 0x00000000
,D/DelayedSyncController( 6634): Delaying sync.
,I/BooksSync( 6614): Starting books sync
D/LgDataFeature( 6657): LgDataFeature() Constructor: none
D/LgDataFeature( 6657): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Killing 5685:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_5685/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6106:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6106/cgroup.procs: No such file or directory
,D/eas_req ( 6657): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6614): started syncMyEbooks
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6715 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 6657): JNI_OnLoad()
I/HubEmail( 6657): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6657): registerNatives()
I/HubEmail( 6657): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6657): registerNativeMethods()
I/HubEmail( 6657): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6657): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6657): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1037): Killing 5710:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_5710/cgroup.procs: No such file or directory
W/Settings( 6657): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1037): Explicit concurrent mark sweep GC freed 65050(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.890ms total 108.695ms
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.google.com, class = 1, type = 1
,I/LgeMiscReceiver( 3304): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3304): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3304): networkInfo.isConnected() = true
D/PhoneState( 3304): setPdpRejectCasuse : false
D/libc-netbsd(  321): res_queryN name = www.google.com succeed
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6749 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/DrmBroadcastReceiver( 6749): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6749): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6749): Service onCreate
D/DrmService( 6749): Received new request = 2
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/DrmSntpClient( 6749): Start Sync process
D/DrmSntpClient( 6749): Server : 0
D/ZenLog  ( 1037): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/libc-netbsd(  321): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6770 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com succeed
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd(  321): res_queryN name = pool.ntp.org succeed
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do add job
D/LgeQuickCoverNotificationData( 1421): add : 2
D/LgeQuickCoverNotificationData( 1421): do add job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/LGDrmClient( 6749): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  331): eDRM_SetDRMTime +++
I/LGDRM   (  331): [DRM] SET TIME : YR=2016, MON=2, DAY=9
I/LGDRM   (  331): [DRM] SET TIME : HR=12, MIN=10, SEC=40
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6770): Almond Protected OAT
V/ILGDrmService(  331): eDRM_SetDRMTime ---
I/DrmSntpClient( 6749): Synched
D/DrmService( 6749): Completed !! request = 2
D/DrmService( 6749): Request count = 0
V/DrmService( 6749): Service onDestroy
I/ActivityManager( 1037): Killing 6171:com.lge.eula/1000 (adj 15): empty #17
,V/FormManager( 6715): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6715): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
I/art     ( 2145): Explicit concurrent mark sweep GC freed 10069(542KB) AllocSpace objects, 3(432KB) LOS objects, 51% free, 30MB/62MB, paused 764us total 30.464ms
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6171/cgroup.procs: No such file or directory
D/WeatherApplication( 6770): removeAccount
,D/WeatherApplication( 6770): Account.length = 0
E/WeatherApplication( 6770): OPERATOR:OPEN
D/WeatherAncestor( 6770): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:10:42
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1037): Killing 5482:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 117682926001; DSPS: 3997699; Offset : -4332611799
D/WeatherAncestor( 6770): connectivity changed - connection : true
D/WeatherService( 6770): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6770): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6770): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6770): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:10:42
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_5482/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6793 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6197:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6197/cgroup.procs: No such file or directory
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ContactsSyncAdapter( 2145): innerSync failed
D/ContactsSyncAdapter( 2145): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2145): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2145): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2145): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2145): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 86930, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7034110708200861581&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 6793): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6793): Loading: webviewchromium
I/LibraryLoader( 6793): Time to load native libraries: 4 ms (timestamps 8239-8243)
,I/LibraryLoader( 6793): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6793): Binding Chromium to main looper Looper (main, tid 1) {6b0f2c3}
,I/LibraryLoader( 6793): Expected native library version number "",actual native library version number ""
I/chromium( 6793): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6793): Initializing chromium process, renderers=0
,W/art     ( 6793): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6793): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6793): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6793): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  325): registerClient() client 0xb57bd0e0, uid 10093
W/AudioManagerAndroid( 6793): Requires BLUETOOTH permission
I/Adreno-EGL( 6793): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6793): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6793): Build Date: 12/12/14 금
I/Adreno-EGL( 6793): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6793): Remote Branch: 
I/Adreno-EGL( 6793): Local Patches: 
I/Adreno-EGL( 6793): Reconstruct Branch: 
,I/NSApplication( 6793): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6849 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 5513:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10014/pid_5513/cgroup.procs: No such file or directory
,W/ResourcesManager( 6849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = mtalk.google.com, class = 1, type = 1
I/iu.SyncManager( 2353): SYNC; picasa accounts
,D/NetworkLogImpl( 2353): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2353): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/GLSActivity( 2145): [ac] getting account id
D/libc-netbsd(  321): res_queryN name = mtalk.google.com succeed
I/GLSUser ( 2145): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/iu.UploadsManager( 2353): num queued entries: 0
I/iu.UploadsManager( 2353): num updated entries: 0
I/iu.SyncManager( 2353): NEXT; no task
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2353): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/PostponalbeReceiver( 5983): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6892 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
E/HttpHelper( 6614): null auth token
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6892): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6892): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6892): [setNextAlert] start
D/Alarms  ( 6892): [setNextAlert] (1)
,D/Alarms  ( 6892):  minTime  = 0
D/Alarms  ( 6892):  -- OK multi -- 0
E/jeny.kim( 6892): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6892): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7034110708200861581&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
I/CommonUtil( 6892): BUILD Country: EU
,D/Alarms  ( 6892): broadcastToWidgetProvider : false
D/Alarms  ( 6892): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1037): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,D/GCM     ( 2145): Connected
,I/DigitalAppWidgetProvider( 6892): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6892): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1459c0d1
,V/DigitalAppWidgetProvider( 6892): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1459c0d1
D/QuickCoverProvider( 6892): onReceiver
D/GCM     ( 2145): Message class com.google.f.a.a.p
,I/indal   ( 1421): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1421): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6770): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:10:43
,D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
D/WeatherService( 6770): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@359cf736
D/ForecastDataCache( 6770): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6770): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6770): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6770): 2 : set auto-update time : 2/9 16:10
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:10:43
,I/ActivityManager( 1037): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6919 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6281:com.google.android.talk/u0a72 (adj 15): empty #17
I/art     (  361): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.421ms total 13.550ms
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 235us total 9.276ms
,I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.077ms
W/libprocessgroup( 1037): failed to open /acct/uid_10072/pid_6281/cgroup.procs: No such file or directory
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 19639(948KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.787ms total 132.046ms
,D/TimeService( 6919): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455019843927
,D/        ( 6919): TimeServiceNative: User Time to be set is 1455019843927
D/QC-time-services( 6919): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6919): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6919): Lib:time_genoff_operation: pargs->ts_val = 1455019843927
D/QC-time-services( 6919): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  433): Daemon: Connection accepted:time_genoff
D/QC-time-services(  433): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455019843927
D/QC-time-services(  433): Daemon:genoff_opr: Base = 2, val = 1455019843927, operation = 0
D/QC-time-services(  433): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/19/70 5:22:46
D/QC-time-services(  433): Daemon:Value read from RTC seconds = 14620966000
D/QC-time-services(  433): Daemon:new time 1455019843927 
D/QC-time-services(  433): Daemon: delta 1440398877927 genoff 1440398877927 
D/QC-time-services(  433): Daemon:genoff_persistent_update: Writing genoff = 1440398877927 to memory
D/QC-time-services(  433): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  433): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  433): Updating the TOD offset
,D/QC-time-services(  433): Daemon:genoff_persistent_update: Writing genoff = 1440398877927 to memory
D/QC-time-services(  433): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  433): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  433): Daemon:Update to modem bit set
D/QC-time-services(  433): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  433): Daemon: Base = 2, Value being sent to MODEM = 1124434077927
E/QC-time-services( 6919): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  433): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  433): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1037): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6938 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1037): Killing 2236:com.lge.music/u0a34 (adj 15): empty #17
I/rmt_storage(  313): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  313): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  313): wakelock acquired: 1, error no: 42
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,V/AudioFlinger(  325): 2236 died, releasing its sessions
V/AudioFlinger(  325):  pid 1873 @ 0
V/AudioFlinger(  325):  pid 3304 @ 1
V/AudioFlinger(  325):  pid 3304 @ 2
W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2236/cgroup.procs: No such file or directory
,I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  313): 
,I/rmt_storage(  313): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  877): [IMS_FATAL]| 3347 | 902 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/ResourcesManager( 6938): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6938): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6938): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6938): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@ac4530c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2d3455, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3def5e6a, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3dabaf5b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@ce993f8, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1459c0d1, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@359cf736, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@10ebe637, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1a1ff7a4, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@9e8990d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3b950c2, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@48eaed3, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3436ea10, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@f12b909, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@54fb70e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2f8b652f, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2888973c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@14a4dcc5, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@ad4361a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@36f3254b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1de5eb28, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@117b8041, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@5ef99e6, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@35cccb27, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@154291d4, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@33bedf7d, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@80b6e72, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@6b0f2c3, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@920f740, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@29def679, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1d9dffbe, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@b25f81f, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@17be476c, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4f8135, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@123659ca, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@cbbf73b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@23fe6e58, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@903fbb1, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@29484896, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@13e8cc17, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@19181804, lg_preferences_recent_tim,ezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1daba1ed, lg_
I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6371): 
I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6371): 
D/GeneralPreferenceUtils( 6938): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
I/jxcore-log( 6371): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6371): 
D/Config  ( 6938): [init]
,I/Config  ( 6938): LGCalendar ver.4.40.16
I/Config  ( 6938): start check model
I/Config  ( 6938): start check native_ca
,I/Config  ( 6938): Config Operator=OPEN, Country=EU
D/Config  ( 6938): [setDefaultValuesToPref]
D/Config  ( 6938): [parseProfiles]
D/ProfilesParser( 6938): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6938): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6938): [updateProfiletoCountryInfo]
D/GeneralPreference( 6938): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6938): [updateWidgets] 
,I/InitNotificationRingtoneService( 6938): Start InitializeAlertRingtoneService.onHandleIntent
,D/MonthWidgetProvider( 6938): [onReceive]
D/CalendarWidgetProvider( 6938): [onReceive]
D/CalendarWidgetProvider( 6938): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6938): onHandleIntent
D/HolidayDataLoader( 6938): readJsonAsset : holiday.json
D/CalendarTypeController( 6938): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6938): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/WeekWidgetProvider( 6938): [onReceive]
D/CalendarWidgetProvider( 6938): [onReceive]
D/CalendarWidgetProvider( 6938): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6938): [onUpdateAndInitCalendarTime]
,I/AlertUtils( 6938): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,E/HolidayIntentService( 6938): onHandleIntent:holiday data empty
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/DigitalAppWidgetProvider( 6892): onReceive: android.intent.action.ALARM_CHANGED
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
D/WeatherAncestor( 6770): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:10:44
D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
D/Weather_cast( 6770): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:10:44
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6938): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/ActivityManager( 1037): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6961 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AlertUtils( 6938): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6938): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1037): Killing 5739:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_5739/cgroup.procs: No such file or directory
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6961): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/jxcore-log( 6371): Test app app.js loaded
I/jxcore-log( 6371): 
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7034110708200861581&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
D/LgDataFeature( 6961): LgDataFeature() Constructor: none
D/LgDataFeature( 6961): LgDataFeature() Constructor Done, null
I/chromium( 6371): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6371): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26eebc2b added. We now have 1 listener(s)
I/jxcore-log( 6371): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6371): 
,I/Babel   ( 6961): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6961): MmsConfig.loadMmsSettings
I/Babel   ( 6961): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6961): MmsConfig.loadFromDatabase
,E/Babel   ( 6961): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6961): MmsConfig.loadFromResources
E/Babel   ( 6961): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6961): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 6961): Unsupported mime audio/evrc
,W/Settings( 6961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6961): Unsupported mime audio/qcelp
W/VideoCapabilities( 6961): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6961): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6961): Unsupported mime audio/qcelp
W/AudioCapabilities( 6961): Unsupported mime audio/evrc
,W/VideoCapabilities( 6961): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6961): Unsupported mime video/divx
W/VideoCapabilities( 6961): Unsupported mime video/divx311
,W/VideoCapabilities( 6961): Unsupported mime video/divx4
W/VideoCapabilities( 6961): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6961): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6961): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 6961): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6961): Unsupported mime audio/eac3
W/AudioCapabilities( 6961): Unsupported mime audio/ac3
,W/AudioCapabilities( 6961): Unsupported mime audio/g726
W/AudioCapabilities( 6961): Unsupported mime audio/wma-voice
,W/AudioCapabilities( 6961): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6961): Unsupported mime audio/adpcm
W/VideoCapabilities( 6961): Unsupported mime video/theora
W/VideoCapabilities( 6961): Unsupported mime video/mjpg
,V/JNIHelp ( 6961): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6961): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6961): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 6961): UserRecoverableAuthException.
,E/Babel   ( 6961): cfq: BadAuthentication
E/Babel   ( 6961): 	at cfn.a(Unknown Source)
E/Babel   ( 6961): 	at f.a(PG:191)
E/Babel   ( 6961): 	at ava.a(PG:88)
E/Babel   ( 6961): 	at ava.a(PG:128)
E/Babel   ( 6961): 	at bjs.a(PG:255)
E/Babel   ( 6961): 	at bep.a(PG:602)
E/Babel   ( 6961): 	at bep.a(PG:469)
E/Babel   ( 6961): 	at bpo.run(PG:1141)
E/Babel   ( 6961): Error getting auth token
E/Babel   ( 6961): bxl
E/Babel   ( 6961): 	at f.a(PG:201)
E/Babel   ( 6961): 	at ava.a(PG:88)
E/Babel   ( 6961): 	at ava.a(PG:128)
E/Babel   ( 6961): 	at bjs.a(PG:255)
E/Babel   ( 6961): 	at bep.a(PG:602)
E/Babel   ( 6961): 	at bep.a(PG:469)
E/Babel   ( 6961): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6961): error sending REQ[fc:4; creat:1455019784830; type:bev-923758102]; took 118 ms (error code == 100)
E/Babel   ( 6961): Account registration failedRedacted-21
E/Babel   ( 6961): bph: null -- null
E/Babel   ( 6961): 	at ava.a(PG:120)
E/Babel   ( 6961): 	at ava.a(PG:128)
E/Babel   ( 6961): 	at bjs.a(PG:255)
E/Babel   ( 6961): 	at bep.a(PG:602)
E/Babel   ( 6961): 	at bep.a(PG:469)
E/Babel   ( 6961): 	at bpo.run(PG:1141)
I/Babel   ( 6961): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6961): Account sign in complete with state 106account: Redacted-21
I/art     ( 6961): Note: end time exceeds epoch: 
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2145): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/Babel   ( 6961): Unexpected exception while authenticating.
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
E/Babel   ( 6961): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6961): 	at cfn.b(Unknown Source)
E/Babel   ( 6961): 	at cfn.a(Unknown Source)
E/Babel   ( 6961): 	at f.a(PG:188)
E/Babel   ( 6961): 	at ava.b(PG:143)
E/Babel   ( 6961): 	at bnr.run(PG:5415)
E/Babel   ( 6961): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6961): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6961): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{39c2aa2f type 2 when 121423 com.android.providers.calendar} when 121423
,I/ActivityManager( 1037): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7003 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,E/BooksSync( 6614): Soft error: 
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7034110708200861581&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
E/BooksSync( 6614): Sync error
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7034110708200861581&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,I/BooksSync( 6614): Finished books sync
W/ResourcesManager( 7003): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26930, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1037): Killing 6455:com.lge.sync/1000 (adj 15): empty #17
,D/CalendarProvider2( 7003): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@a01fa5e
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6455/cgroup.procs: No such file or directory
,D/CalendarProvider2( 7003): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7003): Created com.android.providers.calendar.CalendarAlarmManager@3dabaf5b(com.android.providers.calendar.CalendarProvider2@a01fa5e)
,D/CalendarProviderBroadcastReceiver( 7003): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7003): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 7003): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7003): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 7003): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 7003): (284) automatic index on view_events(_id)
I/GAV2    ( 6614): Thread[GAThread,5,main]: No campaign data found.
D/CalendarProvider2( 7003): [IntentService] Release Lock
,D/CalendarProvider2( 7003): CalendarProviderIntentService.onDestroy()
,I/ActivityManager( 1037): Killing 6084:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6219): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6219): android.os.DeadObjectException
W/System.err( 6219): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6219): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6219): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6219): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,W/System.err( 6219): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6219): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6219): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6219): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6219): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6219): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6219): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6219): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6219): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6219): android.os.DeadObjectException
W/System.err( 6219): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6219): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6219): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6219): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6219): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6219): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6219): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6219): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6219): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6219): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6219): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6219): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6219): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6219): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6084/cgroup.procs: No such file or directory
,W/ActivityManager( 1037): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6219): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6219): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6219): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7040): Quickset Services start...
,I/UEI.SmartControl( 7040): Manufacture = LGE
D/UEI.SmartControl( 7040): Id = LGNevo
D/UEI.SmartControl( 7040): File observer start...
,E/UEI.SmartControl( 7040): IR Port is disabled: false
D/UEI.SmartControl( 7040): Starting file observer...
D/UEI.SmartControl( 7040): Extracting JNI libs...
D/UEI.SmartControl( 7040): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7040): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7040): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7040): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7040): --- Selecting new region: 6
,I/UEI.SmartControl( 7040): Model = LG-D855
D/UEI.SmartControl( 7040): QS Service created
I/UEI.SmartControl( 7040): Service initServices...
,D/UEI.SmartControl( 7040): QS start get config
D/UEI.SmartControl( 7040): Loading JNI Libs...
,I/UEI.SmartControl( 7040): Supports setup maps: true
,D/UEI.SmartControl( 7040): QS start statue = true Error code = 0
,I/UEI.SmartControl( 7040): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7040): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7040): ### init IR Blaster...
D/serial_port( 7040): Configuring serial port
E/UEI.SmartControl( 7040): UEIBLaster setting for 616
I/UEI.SmartControl( 7040): Setting serial record hearder size = 2
I/UEI.SmartControl( 7040): configuring settings for MAXQ616
I/UEI.SmartControl( 7040): Get version...
,D/UEI.SmartControl( 7040): serial port data available: 21
,D/UEI.SmartControl( 7040): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7040): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7040): QS saving settings...
,D/UEI.SmartControl( 7040): IR Blaster version: 25672567
,D/UEI.SmartControl( 7040): serial port data available: 4
,I/UEI.SmartControl( 7040): Device manager: loading config....
,W/ContextImpl( 7040): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 7040): ----------- loading internal config...
E/UEI.SmartControl( 7040): Services init done
D/UEI.SmartControl( 7040): QS Service init finished
D/UEI.SmartControl( 7040): QS Service version name: 2.1.91
D/UEI.SmartControl( 7040): QS Service version code: 201091
D/UEI.SmartControl( 7040): Service requested: Control
,E/UEI.SmartControl( 7040): Loading SETTINGS...
,D/UEI.SmartControl( 7040): Request IControl service: devices are loaded...
,I/ActivityManager( 1037): Killing 6426:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6219): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7040): ------ IControl API: 11
I/UEI.SmartControl( 7040): Registering callback...
I/UEI.SmartControl( 7040): ------ IControl API: 19
I/UEI.SmartControl( 7040): Registering Services Ready callback...
D/UEI.SmartControl( 7040): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7040): Notify AllClients services are ready: 0
I/QRemote ( 6219): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6219): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6219): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6219): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6219): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7040): ------ IControl API: 8
,D/UEI.SmartControl( 7040): -----service ready thread exits
D/QRemote ( 6219): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6219): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6219): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6219): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6219): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6219): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6426/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7040): Internal service binding...
,D/QRemote ( 6219): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6219): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6219): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,D/QRemote ( 6219): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6219): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455019847279]
D/QRemote ( 6219): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6219): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6219): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3106): Thermal-Lib-Client: Client request sent
,I/GAV4    ( 6793): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1037): Killing 6592:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6592/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 5654:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_5654/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7040): Internal timer expired: 1
,D/UEI.SmartControl( 7040): unbind internal service
D/serial_port( 7040): close(fd = 25)
,I/UEI.SmartControl( 7040): Serial port is closed.
I/ActivityManager( 1037): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7084 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{9ea0e35 type 0 when 1455019856366 com.android.vending} when 1455019856366
,D/Finsky  ( 7084): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7084): LgDataFeature() Constructor: none
D/LgDataFeature( 7084): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7084): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1037): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7120 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7084): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7084): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3330): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 7084): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7084): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@15ad6fe9 on behalf of 7084
D/Finsky  ( 7084): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 7120): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7120): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7084): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7120): VM with version 2.1.0 has multidex support
I/MultiDex( 7120): install
I/MultiDex( 7120): VM has multidex support, MultiDex support library is disabled.
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/JNIHelp ( 7120): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7120): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7120): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2845e05d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7120): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2145): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2145): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2353): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1037): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7161 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2353): Restart initialization of location
,W/ResourcesManager( 7161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7161): VM with version 2.1.0 has multidex support
I/MultiDex( 7161): install
I/MultiDex( 7161): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 22007(1012KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.502ms total 89.199ms
,V/JNIHelp ( 7161): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7161): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7161): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2845e05d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7161): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2145): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2145): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2353): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 7161): callingUid 10005, callindPid: 7161
D/LocationInitializer( 2353): Restart initialization of location
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1838): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1838): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/Finsky  ( 7084): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 7084): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/Finsky  ( 7084): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7084): [1] 5.onFinished: Scheduling replication attempt 3.
I/ActivityManager( 1037): Killing 6634:com.android.chrome/u0a57 (adj 15): empty #17
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
I/ActivityManager( 1037): Killing 6715:com.lge.formmanager/u0a26 (adj 15): empty #18
,W/libprocessgroup( 1037): failed to open /acct/uid_10057/pid_6634/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_6715/cgroup.procs: No such file or directory
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{2d6077d0 type 0 when 1455019859986 com.android.vending} when 1455019859986
,D/Finsky  ( 7084): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2145): Explicit concurrent mark sweep GC freed 23507(1383KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 2.024ms total 63.256ms
,W/Finsky  ( 7084): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7084): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/administrator( 1037): Handling package changes for user 0
,I/[SystemUI]QPairHandler( 1480): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/SplitUIService( 1890): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
I/NotificationService( 1037): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7235 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 2087): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[SystemUI]QSlideListController( 1480): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1480): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
,I/AppUp4:AppBoxCP( 7235): onCreate
,W/AppUp4:DB( 7235):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7235):  setFingerPrint start
I/AppUp4:DB( 7235):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AppUp4:DB( 7235):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7235):  SDK version = 21
I/AppUp4:DB( 7235):  beforefinger == newfinger no write in DB
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AppUp4:AppBoxApplication( 7235): AppBoxApplication onCreate()
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppUp4:CustModeStarterReceiver( 7235): onReceive
D/LgDataFeature( 7235): LgDataFeature() Constructor: none
,D/LgDataFeature( 7235): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7235): Context : android.app.ReceiverRestrictedContext@2e2d3455
D/AppUp4:CustFacade( 7235): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7235): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7235): begin check event
I/AppUp4:CustModeStarterReceiver( 7235): Event For Nothing, skip.
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7258 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7084): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 7084): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/ResourcesManager( 7258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7258): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/Finsky  ( 7084): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/ResourcesManager( 7258): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/Finsky  ( 7084): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1838): client connected with version: 7571000
I/ActivityManager( 1037): Killing 6749:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10062/pid_6749/cgroup.procs: No such file or directory
,I/SystemConfig( 7258): BUILD Country: EU
I/SystemConfig( 7258): BUILD Operator: OPEN
,I/ActivityManager( 1037): Killing 6793:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10093/pid_6793/cgroup.procs: No such file or directory
,I/SystemConfig( 7258): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7258): existFile = false
I/SystemConfig( 7258): canReadFile = false
,I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7288 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SystemConfig( 7258): systemFeature RCS result false
D/SystemConfig( 7258): refreshRcsSupport() :false
W/ResourcesManager( 7288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7288): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7288): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7288): Total System Memory = 2995761152
,D/SystemHelper( 7288): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1037): Killing 6849:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6849/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4336): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7319 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/art     (  361): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 334us total 18.657ms
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4336): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,I/art     (  361): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 488us total 19.917ms
,I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 19.470ms
,I/LockScreenSettings( 7319): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7336 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6657:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6657/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 137684582868; DSPS: 4653113; Offset : -4332602673
,W/ResourcesManager( 7336): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2353): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2353): CP2 sync disabled
,I/GLSActivity( 2145): [ac] getting account id
,I/GLSUser ( 2145): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/ActivityManager( 1037): Killing 5983:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5983/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6919:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6919/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=882534823, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1dc7da68 type 2 when 148846 android} when 148846
D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=882534823 [*alarm*], flags=0x0
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 22798(1059KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.434ms total 169.315ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2145): innerSync failed
D/ContactsSyncAdapter( 2145): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2145): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2145): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2145): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2145): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2145): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2145): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 148846, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1037): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 211539, reason: 10019
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 157686689996; DSPS: 5308542; Offset : -4332602273
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1c548457 type 0 when 1455019880326 com.android.vending} when 1455019880326
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7084): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7084): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7084): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 177688688113; DSPS: 5963968; Offset : -4332618422
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{28beb161 type 2 when 179391 android} when 179391
,I/BooksSync( 6614): Starting books sync
,D/BooksSync( 6614): started syncMyEbooks
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8392827399053366331&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
,D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8392827399053366331&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8392827399053366331&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,E/BooksSync( 6614): Soft error: 
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8392827399053366331&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,E/BooksSync( 6614): Sync error
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8392827399053366331&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
I/BooksSync( 6614): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152513, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1480): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1480): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1480): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1480): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
,D/LEDHandler( 1979): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1979): Battery Level Remaining: 100%
D/LEDHandler( 1979): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3728): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1480): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4128): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4128): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{391bb40 type 0 when 1455019909114 com.android.vending} when 1455019909114
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7084): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7084): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7084): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
,I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 197690907481; DSPS: 6619400; Offset : -4332596319
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=882534823, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{14337c22 type 2 when 209432 android} when 209432
D/[Concierge]Service( 2619): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=882534823 [*alarm*], flags=0x0
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2e0a66b3 type 2 when 179451 com.google.android.gms} when 179451
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{272a7470 type 2 when 208903 android} when 208903
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{3d31386e type 0 when 1455019936465 com.android.vending} when 1455019936465
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/VacuumService( 2145): Vacuum at: now=1455019936754 tag=VacuumService
,I/GoogleURLConnFactory( 2145): Using platform SSLCertificateSocketFactory
,W/Uploader( 2145): No account for auth token provided
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7084): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7084): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7084): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2145): No account for auth token provided
,W/Uploader( 2145): No account for auth token provided
,W/Uploader( 2145):  no longer exists, so no auth token.
,W/Uploader( 2145): No account for auth token provided
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 217693031431; DSPS: 7274830; Offset : -4332608443
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 237695120486; DSPS: 7930259; Offset : -4332625204
,I/jxcore-log( 6371): --= Surplus to requirements =--
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): ****TEST TOOK:  ms ****
I/jxcore-log( 6371): 
,I/jxcore-log( 6371): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6371): 
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1bebb382 type 2 when 245187 android} when 245187
,I/BooksSync( 6614): Starting books sync
,D/AndroidRuntime( 7468): 
D/AndroidRuntime( 7468): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7468): CheckJNI is OFF
,D/BooksSync( 6614): started syncMyEbooks
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
,D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 7468): Calling main entry com.android.commands.pm.Pm
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3290632784525868519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6371:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1037): WIN DEATH: Window{378c8928 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
,D/InputDispatcher( 1037): Window went away: Window{378c8928 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{3f5b85e9 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{d2a749d u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{2294a800 6371:com.test.thalitest/u0a311}, curProc for 6371: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{d2a749d u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{d2a749d u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2087): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{13cf6606 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2087): [Launcher.java:903:onResume()]onResume
,I/[LGHome]EVENT( 2087): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{f0874c7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/ActionManagerService( 1924): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2742): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2087): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2087): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2087): [Launcher.java:1114:onPause()]onPause
,D/KeyguardModel( 1480): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2050): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2742): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/System.err( 4258): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4258): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4258): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4258): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4258): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4258): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4258): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4258): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4258): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4258): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4258): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4258): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
I/ActivityManager( 1037): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7511 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1924): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2742): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]QSlideListController( 1480): onReceive = android.intent.action.PACKAGE_REMOVED
,I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2087): , create_time: 1430558575574
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2087): , create_time: 1430558575600
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2087): , create_time: 1454599633839
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
D/KeyguardModel( 1480): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1480): createShortcutInfo...
I/art     ( 1037): Explicit concurrent mark sweep GC freed 37828(2024KB) AllocSpace objects, 8(768KB) LOS objects, 33% free, 44MB/66MB, paused 1.603ms total 174.225ms
I/art     ( 1037): WaitForGcToComplete blocked for 44.548ms for cause Explicit
D/WallpaperManager( 2087): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1480): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1480): createShortcutInfo...
,D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1480): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1480): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 4336): Explicit concurrent mark sweep GC freed 29305(1692KB) AllocSpace objects, 1(19KB) LOS objects, 34% free, 29MB/45MB, paused 1.544ms total 208.735ms
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1480): createShortcutInfo...
,I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1480): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1480): createShortcutInfo...
D/KeyguardModel( 1480): handleShortcutListChanged...
D/KeyguardModel( 1480): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1480): createShortcutInfo...
D/KeyguardModel( 1480): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1480): createShortcutInfo...
,W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1480): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1480): createShortcutInfo...
,D/KeyguardModel( 1480): handleShortcutListChanged...
W/ResourcesManager( 7511): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2087): [Launcher.java:5349:onStop()]onStop
I/art     ( 2087): Background sticky concurrent mark sweep GC freed 4124(214KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 79MB/79MB, paused 5.968ms total 16.442ms
W/art     ( 1037): Suspending all threads took: 11.187ms
,D/PluginManager( 7511): init()
D/administrator( 1037): Handling package changes for user 0
I/art     ( 1037): Explicit concurrent mark sweep GC freed 2973(155KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 12.819ms total 116.293ms
I/art     ( 1037): WaitForGcToComplete blocked for 291.003ms for cause Explicit
I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3106): Thermal-Lib-Client: Client request sent
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3728): [BTUI] [-] updateMediaPlayerInfo
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{1ad99f48 u0 com.lge.launcher2/.Launcher t3} time:246379
,I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2087): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2619): onStartCommand(). Type : 8
D/[Concierge]Service( 2619): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2619): Update widget ID : 11
D/[Concierge]WidgetView( 2087): change position of spinner
D/[Concierge]Service( 2619): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2087): initWebView(). Time : 1455019970806
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
I/[Concierge]WebView( 2087): Return exist ConciergeWebView. Reuse : 758080862
,D/[Concierge]WidgetView( 2087): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[LgeWidgetLib]ExtViewHost( 2087): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@376027a6
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2087): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2087): Widget kill message received. Destory myself. My : 1455019753120, New one : 1455019970806
D/[Concierge]WidgetView( 2087): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2087): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/[Concierge]WidgetView( 2087): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1037): Explicit concurrent mark sweep GC freed 7003(383KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.463ms total 227.786ms
,I/Timeline( 2087): Timeline: Activity_idle id: android.os.BinderProxy@1a675685 time:246543
D/AndroidRuntime( 7468): Shutting down VM
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ExternalStrings( 7511): load override strings
W/ExternalStrings( 7511): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7511): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7511): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7511): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7511): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7511): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7511): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7511): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7511): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7511): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7511): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7511): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7511): onCreate
I/chromium( 2087): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,V/Signer  ( 7511): override build config not found
D/Signer  ( 7511): value of property debug is false
,D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7511): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/GBoardtInterface( 2087): onReloaded()
I/GBoardWebViewClient( 2087): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/LGMDMManager( 7511): Create singleton instance
V/BoardContentProvider( 2742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1924): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2742): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 2742): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2742): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2742): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2742): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2742): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2087): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2087): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2087): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2087): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2087): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2087): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGMDMWrapper( 7511): LG MDM library v4.0.0 is available on this device.
I/art     ( 2145): Explicit concurrent mark sweep GC freed 48115(2MB) AllocSpace objects, 13(1767KB) LOS objects, 51% free, 30MB/62MB, paused 960us total 26.424ms
,D/PostponalbeReceiver( 7511): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7511): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
E/HttpHelper( 6614): null auth token
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/AppUp4:PreloadHelper( 7235): added Exclude : com.test.thalitest
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{3e9915a0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/VoicemailCleanupService( 2164): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7541 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7541): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7541): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7541): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7541): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3290632784525868519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
W/ActivityThread( 7511): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/LGEmail ( 7541): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7541): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,E/SQLiteDatabase( 7511): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.c.run(Unknown Source)
,W/ResourceType( 7541): No package identifier when getting value for resource number 0x00000000
,E/SQLiteDatabase( 7511): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7511): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQ,LiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7511): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7511): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7511): Opened lockedapplications in read-only mode
E/SQLiteDatabase( 7511): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7511): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7511): 	at com.mcafee.d.c.run(Unknown Source)
D/LgDataFeature( 7541): LgDataFeature() Constructor: none
D/LgDataFeature( 7541): LgDataFeature() Constructor Done, null
I/GBoardtInterface( 2087): exportHTML()

```
