#### Test 58135655a685cd3_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2616): mDelayedStopHandler : unbind
,I/MusicBrowser( 2215): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2215): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2215): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2215): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2215): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2215): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1042):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@26b9c048com.lge.music.MediaPlaybackService$5@155cfee1
D/MusicBrowser( 2215): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@30e7d956
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2215): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2215): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2215): reset
V/MediaPlayer[Native]( 2215): setListener
V/MediaPlayer[Native]( 2215): disconnect
V/MediaPlayer[Native]( 2215): destructor
V/AudioFlinger(  322): releasing 13 from 2215 for -1
V/AudioFlinger(  322):  decremented refcount to 0
V/AudioFlinger(  322): purging stale effects
V/MediaPlayer[Native]( 2215): disconnect
D/MusicBrowser( 2215): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2215): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2215): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2215): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2215): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2215): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2215): [SmartShareManagerClient] unregisterListener: 826754054
W/SmartShareClient( 2215): [SmartShareManagerClient] unregisterListener invalid listener: 826754054
I/SmartShareClient( 2215): [SmartShareManagerClient] terminate service: 2215/MediaPlaybackService/594153004
E/HomeCloudIF( 2215): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2215): [SmartShareManagerClient] unbindService context:android.app.Application@14b5fac7
V/CloudHub( 2215): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2215): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2215): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1042): Killing 5000:com.android.calendar/u0a13 (adj 15): empty #17
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29974
W/libprocessgroup( 1042): failed to open /acct/uid_10013/pid_5000/cgroup.procs: No such file or directory
D/AndroidRuntime( 6634): 
D/AndroidRuntime( 6634): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6634): CheckJNI is OFF
D/AndroidRuntime( 6634): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1042): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1982): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1042): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1042): setTaskToReturnTo : TaskRecord{237c463c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1042): setTaskToReturnTo : TaskRecord{237c463c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1042): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1042): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6655 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6634): Shutting down VM
V/ActivityManager( 1042): Display changed displayId=0
D/DSDPConnection( 1876): Display #0 changed.
D/SplitWindowPolicy( 1982): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1982): topRunningActivity=ActivityInfo{a3bff7c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1982): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1982): topRunningActivity=ActivityInfo{394bc005 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6655): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6655): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6655): Loading: webviewchromium
I/LibraryLoader( 6655): Time to load native libraries: 4 ms (timestamps 6127-6131)
I/LibraryLoader( 6655): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6655): Binding Chromium to main looper Looper (main, tid 1) {236a0e2c}
,I/LibraryLoader( 6655): Expected native library version number "",actual native library version number ""
I/chromium( 6655): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6655): Initializing chromium process, renderers=0
,W/art     ( 6655): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  322): registerClient() client 0xb558a2c0, uid 10311
,W/chromium( 6655): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6655): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6655): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1042): Message: 20
D/BluetoothManagerService( 1042): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@116dd0e6:true
I/Adreno-EGL( 6655): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6655): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6655): Build Date: 12/12/14 금
I/Adreno-EGL( 6655): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6655): Remote Branch: 
I/Adreno-EGL( 6655): Local Patches: 
I/Adreno-EGL( 6655): Reconstruct Branch: 
,W/chromium( 6655): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6655): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6655): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6655): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6655): CordovaWebView is running on device made by: LGE
,W/art     ( 6655): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6655): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6655): Render dirty regions requested: true
I/OpenGLRenderer( 6655): Initialized EGL, version 1.4
D/OpenGLRenderer( 6655): Enabling debug mode 0
,D/Atlas   ( 6655): Validating map...
D/SplitWindow( 1042): check instance of lgWin Window{2512ef70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1042): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1042): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1042): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1042): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1042): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ee29c95,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1042): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1464): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1464): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1464):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1464): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6655): LgDataFeature() Constructor: none
D/LgDataFeature( 6655): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1042): Displayed com.test.thalitest/.MainActivity: +606ms (total +707ms)
,I/Timeline( 1042): Timeline: Activity_windows_visible id: ActivityRecord{7b85fc5 u0 com.test.thalitest/.MainActivity t4} time:106564
I/Timeline( 6655): Timeline: Activity_idle id: android.os.BinderProxy@3e235a5c time:106566
I/chromium( 6655): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6655): 
,D/JsMessageQueue( 6655): Set native->JS mode to OnlineEventsBridgeMode
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 6655): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435225856
,I/chromium( 6655): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6655): 
,I/chromium( 6655): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6655): Initializing JXcore engine
W/jxcore-log( 6655): JXcore engine is ready
,W/Thread-764( 6714): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7495]" dev="sockfs" ino=7495 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-764( 6714): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-764( 6714): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[10435]" dev="sockfs" ino=10435 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-764( 6714): type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-764( 6714): type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6655): Starting JXcore engine
,W/jxcore-log( 6655): Platform android
W/jxcore-log( 6655): 
W/jxcore-log( 6655): Process ARCH arm
W/jxcore-log( 6655): 
,I/jxcore-log( 6655): JXcore Cordova bridge is ready!
I/jxcore-log( 6655): 
W/jxcore-log( 6655): JXcore engine is started
,I/jxcore-log( 6655): Toggling radios to true
I/jxcore-log( 6655): 
,D/BluetoothAdapter( 6655): enable(): BT is already enabled..!
D/WifiService( 1042): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1042): setWifiEnabled: true pid=6655, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1042): setWifiEnabled: true pid=6655, uid=10311
,E/WifiService( 1042): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1042): disconnect pid=6655, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1042):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1042): [109,068,817 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1042): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1042): reconnect pid=6655, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6655): Radios toggled
I/jxcore-log( 6655): 
I/jxcore-log( 6655): My device name is: LGE-LG-D855
I/jxcore-log( 6655): 
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1042): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1042): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1042): InitialState.processMessage what=4
D/Tethering( 1042): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1042): DISCONNECT: returned true
E/WifiStateMachine( 1042): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/CommandListener(  317): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1042): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2145): Read error: ssl=0xaf4d5a00: I/O error during system call, Connection timed out
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaf4d5a00: I/O error during system call, Broken pipe
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService( 1042): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager( 1042): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6729 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1042): hidePasspointNotification off =false
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1042): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1042):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1042): [109,208,050 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1042): doBoolean: RECONNECT
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1042): hidePasspointNotification off =false
D/WifiNative-wlan0( 1042): RECONNECT: returned true
E/WifiStateMachine( 1042):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109211
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109212
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WifiNative-wlan0( 1042): SET ps 1: returned true
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  317): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1042): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1042): disableDataServiceNotify
D/DSQN    ( 1042): stop dsqn bin
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109230  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109230  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1042): hidePasspointNotification off =false
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNetworkAgent( 1042): NetworkAgent: NetworkAgent channel lost
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1042): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=109240  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=false, hasIPv4Addr,ess=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1042): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1042): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Disconnected - quitting
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=109246  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1042): Removing idletimer
D/WIFI    ( 1042): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1042): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateSCANNING
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6729): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6729): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1042): StoppedState
,D/DhcpStateMachine( 1042): StoppedState{ when=-190ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1042): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6752 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1042): Killing 6314:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10004/pid_6314/cgroup.procs: No such file or directory
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6729): LgDataFeature() Constructor: none
D/LgDataFeature( 6729): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
I/ActivityManager( 1042): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6776 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1042): Killing 6393:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10008/pid_6393/cgroup.procs: No such file or directory
,W/ResourcesManager( 6776): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     ( 1042): Explicit concurrent mark sweep GC freed 49346(2MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 2.113ms total 136.338ms
,D/QRemote ( 6776): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 6776): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6776): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6776): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6776): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6776): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6776): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6776): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 6776): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6776): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6776): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6776): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6776): LgDataFeature() Constructor: none
D/LgDataFeature( 6776): LgDataFeature() Constructor Done, null
,V/SoundPool( 6776): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 6776): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6776): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6776): doLoad: loading sample sampleID=1
I/QRemote ( 6776): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6776): Start decode
V/MediaPlayer[Native]( 6776): decode(31, 10857164, 17813)
V/MediaPlayerService(  322): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  322): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  322): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] componentName = [9101]
,W/MediaPlayerFactory(  322): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  322): player type = 3
V/AwesomePlayer(  322): AwesomePlayer create()
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/AwesomePlayer(  322): setAudioSink() 
V/AwesomePlayer(  322): reset_l() 
,V/AudioCache(  322): notify(0xb14ce740, 8, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
D/Utils   (  322): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  322): setDataSource_l dataSource
V/LGParserOSAL(  322): SniffLGParser start
V/LGParserOSAL(  322): MainType:5, SubType=0
V/LGParserOSAL(  322): #### check Mime : application/ogg
V/LGParserOSAL(  322): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  322): Use LGExtractor :application/ogg 
I/ActivityManager( 1042): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6799 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6776): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6776): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  322): supported mime: application/ogg
V/AwesomePlayer(  322): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  322): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  322): mBitrate = -1 bits/sec
V/AwesomePlayer(  322): AudioTrack Setting
V/AwesomePlayer(  322): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  322): setAudioSource() 
V/MediaPlayerService(  322): prepare
V/AwesomePlayer(  322): prepareAsync_l() 
V/MediaPlayerService(  322): wait for prepare
V/AwesomePlayer(  322): onPrepareAsyncEvent() 
V/AwesomePlayer(  322): initAudioDecoder() 
W/Utils   (  322): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  322): isOffloadSupported()
V/AudioPolicyManager(  322): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  322): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  322): isAudioPlaybackHookOn() false
V/AwesomePlayer(  322): getUseOffload() = 0 
V/OMXCodec(  322): OMXCodec::Create
V/OMXCodec(  322): findMatchingCodecs()
V/OMXCodec(  322): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  322): matchingCodecs.size()=1
V/OMXCodec(  322): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  322): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  322): LG Codec Adapter start
,V/OMXCodec(  322): OMXCodec Createtor
V/OMXCodec(  322): setComponentRole
V/OMXCodec(  322): configureCodec protected=0
V/LGCodecAdapter(  322): called getLGCodecSpecificData
V/LGCodecOSAL(  322): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  322): Called LGconfigureCodecMETA
V/LGCodecOSAL(  322): Called LGconfigureCodecMSG
V/LGCodecOSAL(  322): Not support LGCodec
V/OMXCodec(  322): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  322): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  322): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  322): Could not offload audio decode, try pcm offload
W/Utils   (  322): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  322): isOffloadSupported()
V/AudioPolicyManager(  322): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  322): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  322): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  322): init()
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  322): allocateBuffers
V/OMXCodec(  322): allocateBuffersOnPort portIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb57fe100 on output port
V/OMXCodec(  322): init() mAsyncCompletion wait!!! 
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  322): init() mAsyncCompletion wait!!! 
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  322): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  322): finishAsyncPrepare_l() 
V/AudioCache(  322): notify(0xb14ce740, 5, 0, 0)
V/AudioCache(  322): ignored
V/AudioCache(  322): notify(0xb14ce740, 1, 0, 0)
V/AudioCache(  322): prepared
V/AudioCache(  322): wait - success
V/MediaPlayerService(  322): start
V/AwesomePlayer(  322): play_l() 
V/AwesomePlayer(  322): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  322): createAudioPlayer_l
V/AwesomePlayer(  322): seekAudioIfNecessary_l() 
V/AwesomePlayer(  322): startAudioPlayer_l() 
D/AudioPlayer(  322): start of Playback, useOffload 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  322): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  322): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mSta,te=4 , newState=7
V/OMXCodec(  322): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045056768
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  322): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  322): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  322): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  322): notify(0xb14ce740, 6, 0, 0)
V/AudioCache(  322): ignored
V/MediaPlayerService(  322): wait for playback complete
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab602000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab603000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab604000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab605000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab606000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab607000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab608000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab609000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60a000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60b000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60c000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60d000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60e000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab60f000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab610000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab611000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab612000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab613000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab614000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab615000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab616000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab617000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab618000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab619000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61a000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61b000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61c000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61d000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61e000, 0xb54eb000, 4096)
,V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab61f000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab620000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab621000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab622000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab623000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab624000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab625000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab626000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab627000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab628000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab629000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62a000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62b000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62c000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62d000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62e000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab62f000, 0xb54eb000, 4096)
,V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab630000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab631000, 0xb54eb000, 4096)
V/LGMDMManager( 6776): Create singleton instance
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab632000, 0xb54eb000, 4096)
V/AudioCache(  322): write(0xb54eb000, 4096)
V/AudioCache(  322): memcpy(0xab633000, 0xb54eb000, 4096)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  322): postAudioEOS() 
V/AudioCache(  322): write(0xb54eb000, 280)
V/AudioCache(  322): memcpy(0xab634000, 0xb54eb000, 280)
V/AwesomePlayer(  322): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  322): onStreamDone
V/AwesomePlayer(  322): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  322): notify(0xb14ce740, 2, 0, 0)
V/AudioCache(  322): playback complete
V/AwesomePlayer(  322): pause_l() 
V/AudioCache(  322): notify(0xb14ce740, 7, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
V/AudioCache(  322): wait - success
V/MediaPlayerService(  322): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  322): Pause Playback at 1068125
V/AwesomePlayer(  322): reset_l() 
V/AudioCache(  322): notify(0xb14ce740, 8, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
D/AudioPlayer(  322): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stopped in state 1
V/,OMXCodec(  322): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  322): AudioPlayer releasing audio source
D/AudioPlayer(  322): AudioPlayer done releasing audio source
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/AwesomePlayer(  322): ~AwesomePlayer call
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/SoundPool( 6776): close(31)
V/SoundPool( 6776): pointer = 0x9fe2b000, size = 205080, sampleRate = 48000, numChannels = 2
D/UEI.SmartControl( 6799): Quickset Services start...
I/UEI.SmartControl( 6799): Manufacture = LGE
D/UEI.SmartControl( 6799): Id = LGNevo
D/UEI.SmartControl( 6799): File observer start...
E/UEI.SmartControl( 6799): IR Port is disabled: false
D/UEI.SmartControl( 6799): Starting file observer...
D/UEI.SmartControl( 6799): Extracting JNI libs...
D/UEI.SmartControl( 6799): --- this system supports 32-bit or 64-bit only
,D/QRemote ( 6776): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6776): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6776): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6416
D/UEI.SmartControl( 6799): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6799): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6799): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6799): --- Selecting new region: 6
,I/UEI.SmartControl( 6799): Model = LG-D855
,D/UEI.SmartControl( 6799): QS Service created
I/UEI.SmartControl( 6799): Service initServices...
,D/UEI.SmartControl( 6799): QS start get config
,D/UEI.SmartControl( 6799): Loading JNI Libs...
,I/UEI.SmartControl( 6799): Supports setup maps: true
,D/UEI.SmartControl( 6799): QS start statue = true Error code = 0
I/UEI.SmartControl( 6799): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6799): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6799): ### init IR Blaster...
,D/serial_port( 6799): Configuring serial port
E/UEI.SmartControl( 6799): UEIBLaster setting for 616
I/UEI.SmartControl( 6799): Setting serial record hearder size = 2
I/UEI.SmartControl( 6799): configuring settings for MAXQ616
I/UEI.SmartControl( 6799): Get version...
D/UEI.SmartControl( 6799): serial port data available: 21
,D/UEI.SmartControl( 6799): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6799): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6799): QS saving settings...
D/UEI.SmartControl( 6799): IR Blaster version: 25672567
,D/UEI.SmartControl( 6799): serial port data available: 4
,I/UEI.SmartControl( 6799): Device manager: loading config....
,D/UEI.SmartControl( 6799): ----------- loading internal config...
W/ContextImpl( 6799): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6799): Services init done
D/UEI.SmartControl( 6799): QS Service init finished
D/UEI.SmartControl( 6799): QS Service version name: 2.1.91
D/UEI.SmartControl( 6799): QS Service version code: 201091
D/UEI.SmartControl( 6799): Service requested: Control
E/UEI.SmartControl( 6799): Loading SETTINGS...
,D/UEI.SmartControl( 6799): Request IControl service: devices are loaded...
I/QRemote ( 6776): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6799): ------ IControl API: 11
I/UEI.SmartControl( 6799): Registering callback...
D/UEI.SmartControl( 6799): Internal service binding...
I/UEI.SmartControl( 6799): ------ IControl API: 19
I/UEI.SmartControl( 6799): Registering Services Ready callback...
D/UEI.SmartControl( 6799): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6799): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6799): -----service ready thread exits
I/QRemote ( 6776): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6776): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,D/QRemote ( 6776): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6776): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6776): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6799): ------ IControl API: 8
D/QRemote ( 6776): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6776): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6776): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6776): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6776): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6776): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6776): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6776): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6776): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,D/QRemote ( 6776): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6776): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454591133637]
D/QRemote ( 6776): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1042): Killing 6114:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 6776): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1042): Killing 5783:com.lge.appbox.client/u0a11 (adj 15): empty #18
,I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1042):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2058 bcn=0
E/WifiStateMachine( 1042):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2058 bcn=0
E/WifiStateMachine( 1042):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2058 bcn=0
E/WifiStateMachine( 1042):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2058 bcn=0
D/WifiNative-wlan0( 1042): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=111329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/libprocessgroup( 1042): failed to open /acct/uid_10019/pid_6114/cgroup.procs: No such file or directory
,W/libprocessgroup( 1042): failed to open /acct/uid_10011/pid_5783/cgroup.procs: No such file or directory
V/QRemote ( 6776): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6776): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=111480  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATING
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 2674): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=43 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=111637  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=111639  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{1c268c2a type 0 when 1454591131798 com.android.vending} when 1454591131798
,E/WifiStateMachine( 1042):  DisconnectedState CMD_ASSOCIATED_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111645
D/Tethering( 1042): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1042):  ConnectModeState CMD_ASSOCIATED_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111646
E/WifiStateMachine( 1042):  DriverStartedState CMD_ASSOCIATED_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111646
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_ASSOCIATED_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111647
E/WifiStateMachine( 1042):  DefaultState CMD_ASSOCIATED_BSSID 43 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111647
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=111648  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1042): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1042): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATED
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=111659  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=111660  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=111661  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1042):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111661
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111661
D/WifiNative-wlan0( 1042): doString: [STATUS]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1042):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/WifiServiceExtension( 1042): setVHTCapabilityType  : false
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1042): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1042): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1042): Got NetworkAgent Messenger
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1042): NetworkAgent connected
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
,D/CommandListener(  317): Setting iface cfg
E/WifiStateMachine( 1042): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1042): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState
E/WifiStateMachine( 1042):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=111716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=111717  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=111717  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateGROUP_HANDSHAKE
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=111719  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=111719  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=111720  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/SIM_STK ( 1042): Menu title from STK is T-Mobile
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ContextImpl( 4328): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 0
D/WifiNative-wlan0( 1042): SET ps 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1042): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): DHCP Start wake lock is acquired.
,D/CommandListener(  317): Setting iface cfg
D/CommandListener(  317): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1042): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateCOMPLETED
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1042):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1042): SET ps 1: returned true
E/WifiStateMachine( 1042):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1042): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1042): Adding iface wlan0 to network 101
E/WifiStateMachine( 1042): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 1
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService( 1042): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1042): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1042): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  317): netlink response contains error (File exists)
D/ConnectivityService( 1042): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1042): addLocalRoutetoDefaultNetwork
,D/ConnectivityService( 1042): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1042): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1042): currentScore = 0, newScore = 20
D/ConnectivityService( 1042):    accepting network in place of null
D/ConnectivityService( 1042): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyNetworkFactory-1( 1876): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1042): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1042): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1042): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1042): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: fa,lse, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1042): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1042): validation of new default Network = false
D/ConnectivityService( 1042): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1042): enableDataServiceNotify 
D/DSQN    ( 1042): start dsqn bin
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NetworkPolicy( 1042): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/dsqn    ( 6854): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6854): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/DSQN    ( 6854): DSQN ssw
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGDataListener(  317): argv[0]=dsqncommand
D/LGDataListener(  317): argv[1]=wlan0
D/LGDataListener(  317): argv[2]=1
D/LGDataListener(  317): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/DSQN    ( 1042): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1042): start to monitor internet connection
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:05:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591134417], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591134395]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Validated
,D/ConnectivityService( 1042): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1042): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1042): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1876): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1042): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1042): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1042): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6860): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6860): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6860): version 5.5.6 starting
E/dhcpcd  ( 6860): get_duid: m
D/dhcpcd  ( 6860): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6860): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dhcpcd  ( 6860): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6860): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6860): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6860): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6860): wlan0: sending REQUEST (xid 0x665e8c28), next in 3.27 seconds
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6187): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6187): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6187): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering( 1042): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=true
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/Tethering( 1042): MasterInitialState.processMessage what=3
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1042): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6870 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/art     (  346): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 17.858ms
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 35.113ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 18.451ms
,I/ActivityManager( 1042): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6887 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6887): onCreate
W/AppUp4:DB( 6887):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6887):  setFingerPrint start
I/AppUp4:DB( 6887):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/ReaderUtils( 6870): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,I/AppUp4:DB( 6887):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6887):  SDK version = 21
I/AppUp4:DB( 6887):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6887): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/LgDataFeature( 6887): LgDataFeature() Constructor: none
D/LgDataFeature( 6887): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
,I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6887): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6887): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6887): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6887): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1042): Killing 6415:com.lge.email/u0a23 (adj 15): empty #17
,W/GAV2    ( 6870): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/libprocessgroup( 1042): failed to open /acct/uid_10023/pid_6415/cgroup.procs: No such file or directory
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3328): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4197): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3328): DownloadService onCreate
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3328): in removeSpuriousFiles
,V/DownloadManager( 3328): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@1c064453 on behalf of 3328
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3328): in trimDatabase
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@2ae9190 on behalf of 3328
I/ActivityManager( 1042): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6915 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4197): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3328): DownloadService onStartCommand
V/DownloadManager( 3328): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/BooksApp( 6870): Created application version: 3.2.35 (30235)
D/LGDMClient( 4197): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4197): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@12a6d2af on behalf of 3328
,V/DownloadManager( 3328): processing inserted download 1
V/DownloadManager( 3328): processing inserted download 4
V/DownloadManager( 3328): processing inserted download 7
V/DownloadManager( 3328): processing inserted download 8
V/DownloadManager( 3328): processing inserted download 9
V/DownloadManager( 3328): processing inserted download 10
V/DownloadManager( 3328): processing inserted download 16
V/DownloadManager( 3328): processing inserted download 17
V/DownloadManager( 3328): processing inserted download 18
V/DownloadManager( 3328): processing inserted download 21
V/DownloadManager( 3328): processing inserted download 22
V/DownloadManager( 3328): DownloadService onDestroy
,W/ResourcesManager( 6915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6915): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6915): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6915): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/BooksSync( 6870): Starting books sync
E/WifiStateMachine( 1042):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1042): identical MTU - not setting
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524295
I/LGEmail ( 6915): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6915): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6915): No package identifier when getting value for resource number 0x00000000
,D/BooksSync( 6870): started syncMyEbooks
,D/LgDataFeature( 6915): LgDataFeature() Constructor: none,
,D/LgDataFeature( 6915): LgDataFeature() Constructor Done, null
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
E/HttpHelper( 6870): null auth token
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/eas_req ( 6915): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/libc-netbsd(  317): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/dhcpcd  ( 6860): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/libc-netbsd(  317): res_queryN name = www.googleapis.com succeed
,I/ActivityManager( 1042): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6947 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/dhcpcd  ( 6860): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6860): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6860): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6860): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6860): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/HubEmail( 6915): JNI_OnLoad()
I/HubEmail( 6915): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6915): registerNatives()
I/HubEmail( 6915): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6915): registerNativeMethods()
I/HubEmail( 6915): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6915): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1042): Killing 5733:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dhcpcd  ( 6860): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6860): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6860): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1042): failed to open /acct/uid_10027/pid_5733/cgroup.procs: No such file or directory
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6655): 
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
,I/ActivityManager( 1042): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6989 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5297288238185514591&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com succeed
,D/DhcpStateMachine( 1042): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1042): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1042): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1042): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1042): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1042): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1042): RunningState
V/FormManager( 6947): There are no updated forms. The schedule will be deleted.
V/FormManager( 6947): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1042): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7011 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1042): Killing 6451:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1042): failed to open /acct/uid_10061/pid_6451/cgroup.procs: No such file or directory
,I/ActivityManager( 1042): Killing 6488:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10080/pid_6488/cgroup.procs: No such file or directory
,I/ActivityManager( 1042): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7031 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1042): Killing 5976:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6655): 
,W/libprocessgroup( 1042): failed to open /acct/uid_10097/pid_5976/cgroup.procs: No such file or directory
,I/art     ( 7031): Almond Protected OAT
,I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6655): 
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6655): 
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6655): 
,D/WeatherApplication( 7031): removeAccount
D/WeatherApplication( 7031): Account.length = 0
E/WeatherApplication( 7031): OPERATOR:OPEN
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:36
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:null
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6655): 
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is not up-to-date, count: 0
I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6655): 
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:36
,E/WifiStateMachine( 1042):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1042):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1042):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1042):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1042):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/ActivityManager( 1042): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7049 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1042): Killing 6520:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1042): failed to open /acct/uid_1000/pid_6520/cgroup.procs: No such file or directory
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
,D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5297288238185514591&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
I/art     ( 1042): Explicit concurrent mark sweep GC freed 56873(2MB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 2.188ms total 137.849ms
,V/WifiInternetCheck( 1042): Single check msg out of sync, ignoring.
,I/WebViewFactory( 7049): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7049): Loading: webviewchromium
,I/LibraryLoader( 7049): Time to load native libraries: 4 ms (timestamps 4835-4839)
I/LibraryLoader( 7049): Expected native library version number "",actual native library version number ""
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1042): MasterInitialState.processMessage what=3
V/WebViewChromiumFactoryProvider( 7049): Binding Chromium to main looper Looper (main, tid 1) {b49a81d}
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LibraryLoader( 7049): Expected native library version number "",actual native library version number ""
I/chromium( 7049): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7049): Initializing chromium process, renderers=0
,W/art     ( 7049): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7049): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7049): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7049): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  322): registerClient() client 0xb57f4f40, uid 10093
W/AudioManagerAndroid( 7049): Requires BLUETOOTH permission
I/Adreno-EGL( 7049): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7049): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7049): Build Date: 12/12/14 금
I/Adreno-EGL( 7049): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7049): Remote Branch: 
I/Adreno-EGL( 7049): Local Patches: 
I/Adreno-EGL( 7049): Reconstruct Branch: 
,I/NSApplication( 7049): Starting up...
,I/ActivityManager( 1042): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7111 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1042): Killing 5569:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10005/pid_5569/cgroup.procs: No such file or directory
,W/ResourcesManager( 7111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19964
,D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3328): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3328): DownloadService onCreate
I/LGDMClient( 4197): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3328): in removeSpuriousFiles
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/LGDMClient( 4197): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4197): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4197): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@3922a19a on behalf of 3328
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
V/DownloadManager( 3328): DownloadService onStartCommand
,V/DownloadManager( 3328): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@fbb02a8 on behalf of 3328
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:38
V/DownloadManager( 3328): processing inserted download 1
V/DownloadManager( 3328): processing inserted download 4
V/DownloadManager( 3328): processing inserted download 7
V/DownloadManager( 3328): processing inserted download 8
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
,V/DownloadManager( 3328): processing inserted download 9
I/DownloadManager( 3328): in trimDatabase
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3328): processing inserted download 10
V/DownloadManager( 3328): processing inserted download 16
V/DownloadManager( 3328): processing inserted download 17
V/DownloadManager( 3328): processing inserted download 18
V/DownloadManager( 3328): processing inserted download 21
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
I/art     ( 2145): Explicit concurrent mark sweep GC freed 25412(1489KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.651ms total 37.859ms
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:38
V/DownloadManager( 3328): processing inserted download 22
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@235f81c1 on behalf of 3328
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3328): DownloadService onDestroy
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/FormManager( 6947): There are no updated forms. The schedule will be deleted.
V/FormManager( 6947): Alarm would be updated, because LastCheckTime has been updated.
,D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
W/Kids    ( 2369): [AccountUtils] Account not ready
W/Kids    ( 2369): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2369): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2369): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
I/GLSActivity( 2145): [ac] getting account id
,I/GLSUser ( 2145): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3328): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3328): DownloadService onCreate
,I/LGDMClient( 4197): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3328): in removeSpuriousFiles
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@283868a7 on behalf of 3328
E/LGDMClient( 4197): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4197): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3328): in trimDatabase
D/LGDMClient( 4197): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@2811a154 on behalf of 3328
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3328): DownloadService onStartCommand
V/DownloadManager( 3328): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = true
D/PhoneState( 3257): setPdpRejectCasuse : false
D/LgeQuickCoverNLService( 1423): onNotificationPosted
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@33f8e843 on behalf of 3328
W/Kids    ( 2369): [AccountUtils] Account not ready
W/Kids    ( 2369): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2369): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2369): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3328): processing inserted download 1
V/DownloadManager( 3328): processing inserted download 4
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
V/DownloadManager( 3328): processing inserted download 7
W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5297288238185514591&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/DownloadManager( 3328): processing inserted download 8
V/DownloadManager( 3328): processing inserted download 9
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
V/DownloadManager( 3328): processing inserted download 10
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
V/DownloadManager( 3328): processing inserted download 16
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
V/DownloadManager( 3328): processing inserted download 17
V/DownloadManager( 3328): processing inserted download 18
V/DownloadManager( 3328): processing inserted download 21
V/DownloadManager( 3328): processing inserted download 22
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:38
,V/DownloadManager( 3328): DownloadService onDestroy
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:38
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 6947): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6947): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2369): [AccountUtils] Account not ready
W/Kids    ( 2369): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2369): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2369): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = www.google.com succeed
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1042): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 6799): Internal timer expired: 1
,D/UEI.SmartControl( 6799): unbind internal service
D/serial_port( 6799): close(fd = 25)
,I/UEI.SmartControl( 6799): Serial port is closed.
E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5297288238185514591&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5297288238185514591&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): ,	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
,I/ActivityManager( 1042): Killing 6551:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 99322, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1042): failed to open /acct/uid_1000/pid_6551/cgroup.procs: No such file or directory
,I/GAV2    ( 6870): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 117792878292; DSPS: 4000521; Offset : -4308041625
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{29d88199 type 2 when 118826 com.google.android.gms} when 118826
,V/QRemote ( 6776): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6776): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6416
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
I/GAV4    ( 7049): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6655): Test app app.js loaded
I/jxcore-log( 6655): 
,I/chromium( 6655): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d83c67e added. We now have 1 listener(s)
,I/jxcore-log( 6655): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6655): 
,I/ActivityManager( 1042): Killing 6256:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10014/pid_6256/cgroup.procs: No such file or directory
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{3f9250c type 2 when 126578 android} when 126578
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1042): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1042): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1042): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1042): InitialState.processMessage what=4
,D/Tethering( 1042): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1042):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=134328
E/WifiStateMachine( 1042):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=134328
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=134329
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/CommandListener(  317): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1042): RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,V/NativeCrypto( 2145): Read error: ssl=0xaf4d3e00: I/O error during system call, Connection timed out
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaf4d3e00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1042): WifiStateMachine: Leaving Connected state
,D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService( 1042): ignoring duplicate network state non-change
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 0
D/WifiHS20( 1042): hidePasspointNotification off =false
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1042): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{1eed806a type 0 when 1454591154515 com.android.vending} when 1454591154515
E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=134513  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=134514  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=134514  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1042): hidePasspointNotification off =false
D/ConnectivityService( 1042): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1042): disableDataServiceNotify
D/DSQN    ( 1042): stop dsqn bin
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=134523  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1042): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1042): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1042): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1042): Removing idletimer
W/Settings( 1042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1042): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Disconnected - quitting
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1042): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1042): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateSCANNING
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/SIM_STK ( 1042): Menu title from STK is T-Mobile
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/DhcpStateMachine( 1042): StoppedState
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6187): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6187): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6187): [1] 5.onFinished: Scheduling replication attempt 3.
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1042):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
D/WifiNative-wlan0( 1042): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136520  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=136550  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/wpa_supplicant( 2674): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering( 1042): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1042): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136651  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=136652  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1042):  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=136655
E/WifiStateMachine( 1042):  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=136657
E/WifiStateMachine( 1042):  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=136657
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=136659
E/WifiStateMachine( 1042):  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=136659
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136660  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=136686  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATED
V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{ac25be6 type 2 when 136690 com.google.android.gms} when 136690
,D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateFOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6887): onReceive
,D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
,D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:0
,D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:0
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 6947): Network not available. Please check & try again.
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,V/FormManager( 6947): Network unavailable.
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 6947): Network unavailable.
,I/iu.Environment( 2369): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2369): num queued entries: 0
I/iu.UploadsManager( 2369): num updated entries: 0
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 2369): NEXT; no task
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 137794750941; DSPS: 4655942; Offset : -4308032476
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/art     ( 1042): Explicit concurrent mark sweep GC freed 69891(3MB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.938ms total 89.161ms
,D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
V/FormManager( 6947): Network unavailable.
W/FormManager( 6947): Network not available. Please check & try again.
V/FormManager( 6947): Network unavailable.
,D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:0
,D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:0
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 2674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139677  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139679  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateGROUP_HANDSHAKE
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1042): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1042): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1042):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139694
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139695
D/WifiNative-wlan0( 1042): doString: [STATUS]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1042):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1042): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1042): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1042): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/ConnectivityService( 1042): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1042): Got NetworkAgent Messenger
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1042): NetworkAgent connected
,D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
,D/CommandListener(  317): Setting iface cfg
D/DhcpStateMachine( 1042): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState
E/WifiStateMachine( 1042): Start Dhcp Watchdog 3
E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139778  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139784  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139784  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 0
D/WifiNative-wlan0( 1042): SET ps 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1042): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): DHCP Start wake lock is acquired.
D/CommandListener(  317): Setting iface cfg
D/CommandListener(  317): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper( 1042): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1042):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/ConnectivityService( 1042): ignoring duplicate network state non-change
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1042): Adding iface wlan0 to network 102
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1042): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 1042): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1042): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService( 1042): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
E/Netd    (  317): netlink response contains error (File exists)
D/ConnectivityService( 1042): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1042): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
D/ConnectivityService( 1042): Setting Dns servers for network 102 to [/192.168.1.1]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1042): currentScore = 0, newScore = 20
D/ConnectivityService( 1042):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Connected
D/ConnectivityService( 1042): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1042): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1876): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1042): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1042): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=t,rue
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 28
,D/LocSvc_java( 1042): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/CSLegacyTypeTracker( 1042): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1042): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1042): validation of new default Network = false
D/ConnectivityService( 1042): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1042): enableDataServiceNotify 
D/DSQN    ( 1042): start dsqn bin
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/dsqn    ( 7326): type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7326): type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
E/DSQN    ( 7326): DSQN ssw
,V/NetworkPolicy( 1042): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine( 1042): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1042): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1042): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/dhcpcd  ( 7331): type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7331): type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGDataListener(  317): argv[0]=dsqncommand
D/LGDataListener(  317): argv[1]=wlan0
D/LGDataListener(  317): argv[2]=1
D/LGDataListener(  317): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1042): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1042): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
I/dhcpcd  ( 7331): version 5.5.6 starting
E/dhcpcd  ( 7331): get_duid: m
D/dhcpcd  ( 7331): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7331): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:06:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591162511], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591162484]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Validated
,D/ConnectivityService( 1042): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1876): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7331): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7331): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7331): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7331): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 7331): wlan0: sending REQUEST (xid 0x653e5b35), next in 4.25 seconds
E/WifiStateMachine( 1042):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
D/ConnectivityService( 1042): identical MTU - not setting
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524295
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{238a1c34 type 2 when 141126 com.google.android.gms} when 141126
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = mtalk.google.com, class = 1, type = 1
I/dhcpcd  ( 7331): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
I/dhcpcd  ( 7331): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7331): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7331): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7331): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7331): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7331): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7331): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7331): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  317): res_queryN name = mtalk.google.com succeed
,D/DhcpStateMachine( 1042): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1042): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1042): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1042): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1042): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1042): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1042): RunningState
D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
,V/WifiInternetCheck( 1042): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
,D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3328): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/eas_req ( 6915): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3328): DownloadService onCreate
I/DownloadManager( 3328): in removeSpuriousFiles
,V/DownloadManager( 3328): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@2111a7f9 on behalf of 3328
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3328): DownloadService onStartCommand
V/DownloadManager( 3328): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4197): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@46fc6ec on behalf of 3328
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = true
D/PhoneState( 3257): setPdpRejectCasuse : false
I/DownloadManager( 3328): in trimDatabase
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 4197): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:5
D/LGDMClient( 4197): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4197): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@38bbcab5 on behalf of 3328
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:6:5
V/DownloadManager( 3328): processing inserted download 1
,V/DownloadManager( 3328): processing inserted download 4
V/DownloadManager( 3328): processing inserted download 7
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com, class = 1, type = 1
V/DownloadManager( 3328): processing inserted download 8
V/DownloadManager( 3328): processing inserted download 9
V/DownloadManager( 3328): processing inserted download 10
V/DownloadManager( 3328): processing inserted download 16
V/DownloadManager( 3328): processing inserted download 17
V/DownloadManager( 3328): processing inserted download 18
V/DownloadManager( 3328): processing inserted download 21
V/DownloadManager( 3328): processing inserted download 22
,V/DownloadManager( 3328): DownloadService onDestroy
,D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2369): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2369): num queued entries: 0
I/iu.UploadsManager( 2369): num updated entries: 0
,I/iu.SyncManager( 2369): NEXT; no task
,D/ConnectivityService( 1042): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on "NG700"
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:06:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591165674], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591165655]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Validated
D/ConnectivityService( 1042): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2369): [AccountUtils] Account not ready
W/Kids    ( 2369): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2369): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2369): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 6947): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6947): Alarm would be updated, because LastCheckTime has been updated.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = www.google.com succeed
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1042): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{1c772eda type 2 when 149593 com.google.android.gms} when 149593
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
,E/WifiStateMachine( 1042):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1042):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1042):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{ce171e8 type 0 when 1454591177406 com.android.vending} when 1454591177406
,V/SIM_STK ( 1042): Menu title from STK is T-Mobile
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6187): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6187): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6187): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 157796998067; DSPS: 5311376; Offset : -4308044145
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 177798593529; DSPS: 5966788; Offset : -4308035727
,V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{3b850fb type 0 when 1454591197761 com.android.vending} when 1454591197761
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{1b492518 type 2 when 179261 com.google.android.gms} when 179261
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1042): Menu title from STK is T-Mobile
,I/VacuumService( 2145): Vacuum at: now=1454591202117 tag=VacuumService
,I/GoogleURLConnFactory( 2145): Using platform SSLCertificateSocketFactory
,W/Uploader( 2145): No account for auth token provided
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1042):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1042):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1042):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
E/WifiStateMachine( 1042):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6187): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6187): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6187): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 2145): No account for auth token provided
,W/Uploader( 2145):  no longer exists, so no auth token.
,W/Uploader( 2145): No account for auth token provided
V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{18dd1460 type 2 when 180255 android} when 180255
,I/BooksSync( 6870): Starting books sync
,D/BooksSync( 6870): started syncMyEbooks
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1423): Notification difference=198
,D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2336911506759038013&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2336911506759038013&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
W/ResourcesManager( 1423): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1423): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
,D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2336911506759038013&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2336911506759038013&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
,E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2336911506759038013&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 180255, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1042): battery changed pluggedType: 2
D/HeadsetStateMachine( 3760): Disconnected process message: 10, size: 0
D/LEDHandler( 1982): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1982): Battery Level Remaining: 100%
D/LEDHandler( 1982): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 197802021230; DSPS: 6622261; Offset : -4308056512
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{14ea599f type 2 when 208142 android} when 208142
V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{3f10caec type 2 when 210316 android} when 210316
V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{d29494a type 0 when 1454591222367 com.android.vending} when 1454591222367
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,V/SIM_STK ( 1042): Menu title from STK is T-Mobile
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6187): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6187): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6187): [1] 5.onFinished: Giving up after 6 failures.
I/art     ( 1042): Explicit concurrent mark sweep GC freed 70068(3MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.639ms total 170.955ms
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1042): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1042): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1042): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1042):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=215372
E/WifiStateMachine( 1042):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=215372
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=215373
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1042): InitialState.processMessage what=4
D/Tethering( 1042): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
,D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[]
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
,D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/CommandListener(  317): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1042): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2145): Read error: ssl=0xaf4d3e00: I/O error during system call, Connection timed out
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaf4d3e00: I/O error during system call, Broken pipe
,D/ConnectivityService( 1042): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiHS20( 1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1042): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=215542  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=215543  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1042): hidePasspointNotification off =false
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=215548  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiHS20( 1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=215556  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNetworkAgent( 1042): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateSCANNING
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1042): disableDataServiceNotify
,D/DSQN    ( 1042): stop dsqn bin
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/ConnectivityService( 1042): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Disconnected - quitting
D/CSLegacyTypeTracker( 1042): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1042): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService( 1042): Removing idletimer
W/Settings( 1042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1042): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1042): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1042): StoppedState
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/wpa_supplicant( 2674): [LGE_PATCH]scan interval[0] = 2 sec.
,D/WfdsMonitor( 1982): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1982): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=70 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=71 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1042): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=72 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1042):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
D/WifiNative-wlan0( 1042): doString: [BSS RANGE=0- MASK=0x21987]
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 217804139296; DSPS: 7277690; Offset : -4308044055
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
,D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:21
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:21
W/FormManager( 6947): Network not available. Please check & try again.
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 6947): Network unavailable.
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/FormManager( 6947): Network unavailable.
,I/iu.Environment( 2369): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2369): num queued entries: 0
I/iu.UploadsManager( 2369): num updated entries: 0
I/iu.SyncManager( 2369): NEXT; no task
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
,D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/FormManager( 6947): Network not available. Please check & try again.
,W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
V/FormManager( 6947): Network unavailable.
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:21
,V/FormManager( 6947): Network unavailable.
D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
,D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:21
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=73 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2674): [LGE_PATCH]scan interval[1] = 3 sec.
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiStateMachine( 1042):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
E/WifiStateMachine( 1042):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2058 bcn=0
D/WifiNative-wlan0( 1042): doString: [BSS RANGE=0- MASK=0x21987]
D/WfdsMonitor( 1982): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1982): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=75 dispatchEvent: WPS-AP-AVAILABLE 
,W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
,E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=76 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1042): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=77 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
V/AlarmManager( 1042): RTC_WAKEUP set : Alarm{3633f377 type 0 when 1454591238212 android} when 1454591238212
,E/WifiStateMachine( 1042):  DisconnectedState CMD_START_SCAN -2 -2 ic=2 proc(ms):3 dur:2058 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:158423] from screen [on:0 period:-1402667619]
V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{2d571be4 type 2 when 223246 com.google.android.gms} when 223246
E/WifiStateMachine( 1042):  ConnectModeState CMD_START_SCAN -2 -2 ic=2 proc(ms):18 dur:2058 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:22] from screen [on:0 period:-1402667597]
E/WifiStateMachine( 1042):  DriverStartedState CMD_START_SCAN -2 -2 ic=2 proc(ms):26 dur:2058 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1402667596]
D/WifiNative-wlan0( 1042): doBoolean: SCAN
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1042): SCAN: returned true
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1042): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=80 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1042): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1042):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1042):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1042):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1042):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1042): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 81 0 rt=225422  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 81 0 rt=225449  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6729): Not supported operator for automatic switch
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2674): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=82 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1042): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=83 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=84 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=225529  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=225529  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1042):  DisconnectedState CMD_ASSOCIATED_BSSID 83 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=225530
E/WifiStateMachine( 1042):  ConnectModeState CMD_ASSOCIATED_BSSID 83 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=225530
E/WifiStateMachine( 1042):  DriverStartedState CMD_ASSOCIATED_BSSID 83 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=225530
I/wpa_supplicant( 2674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=85 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1042): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=86 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1042): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=87 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1042): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=88 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_ASSOCIATED_BSSID 83 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=225554
E/WifiStateMachine( 1042):  DefaultState CMD_ASSOCIATED_BSSID 83 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=225554
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 84 0 rt=225555  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 84 0 rt=225582  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 85 0 rt=225590  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 85 0 rt=225592  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1042):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225594
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=225595
D/WifiNative-wlan0( 1042): doString: [STATUS]
,D/WifiNative-wlan0( 1042):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=89 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1042): setVHTCapabilityType  : false
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/WifiServerServiceExt( 1042): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1042): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1042): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1042): Got NetworkAgent Messenger
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1042): NetworkAgent connected
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CommandListener(  317): Setting iface cfg
E/WifiStateMachine( 1042): Start Dhcp Watchdog 4
D/DhcpStateMachine( 1042): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState
,E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 88 0 rt=225645  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 88 0 rt=225646  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 88 0 rt=225646  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 89 0 rt=225649  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 89 0 rt=225649  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 89 0 rt=225650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 103]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 0
D/WifiNative-wlan0( 1042): SET ps 0: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1042): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c211359 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1042): DHCP Start wake lock is acquired.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CommandListener(  317): Setting iface cfg
D/CommandListener(  317): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1042): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1042):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1042): setSupplicantStateCOMPLETED
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 103]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1042):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1042): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 103]; created=false
E/WifiStateMachine( 1042):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1042): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1042): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHAN,GED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1042): Adding iface wlan0 to network 103
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1042): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1042): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1042): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1042): Adding Route [fe80::/64 -> :: wlan0] to network 103
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1042): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
E/Netd    (  317): netlink response contains error (File exists)
D/ConnectivityService( 1042): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
D/ConnectivityService( 1042): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1042): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 103
D/ConnectivityService( 1042): Setting Dns servers for network 103 to [/192.168.1.1]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1042): currentScore = 0, newScore = 20
D/ConnectivityService( 1042):    accepting network in place of null
D/ConnectivityService( 1042): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1876): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1042): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1042): Sending, connected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1042): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1042): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1042): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1042): validation of new default Network = false
D/ConnectivityService( 1042): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1042): enableDataServiceNotify 
D/DSQN    ( 1042): start dsqn bin
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
W/dsqn    ( 7645): type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7645): type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1042): [LG_RESTRICTED] checkMobilePolicy_type()
,E/DSQN    ( 7645): DSQN ssw
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  317): argv[0]=dsqncommand
D/LGDataListener(  317): argv[1]=wlan0
D/LGDataListener(  317): argv[2]=1
,D/LGDataListener(  317): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1042): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1042): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6776): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6776): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6776): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:07:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591248325], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591248301]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Validated
D/ConnectivityService( 1042): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1042):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1042): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
,D/ConnectivityService( 1042): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1876): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/DhcpStateMachine( 1042): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1042): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1042): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7652): type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7652): type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7652): version 5.5.6 starting
E/dhcpcd  ( 7652): get_duid: m
D/dhcpcd  ( 7652): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7652): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7652): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7652): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7652): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7652): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7652): wlan0: sending REQUEST (xid 0x709dbf4b), next in 3.26 seconds
,E/WifiStateMachine( 1042):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7652): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1042): Update of LinkProperties for NetworkAgentInfo [WIFI () - 103]; created=true
D/ConnectivityService( 1042): identical MTU - not setting
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1042): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524295
I/dhcpcd  ( 7652): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7652): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7652): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7652): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7652): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7652): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7652): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7652): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/DhcpStateMachine( 1042): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1042): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1042): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1042): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
,V/LgDhcpStateMachineHelper( 1042): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1042): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1042): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine( 1042): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1042): RunningState,
V/WifiInternetCheck( 1042): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3328): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/eas_req ( 6915): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3328): DownloadService onCreate
I/DownloadManager( 3328): in removeSpuriousFiles
,I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3257): networkInfo.isConnected() = true
D/PhoneState( 3257): setPdpRejectCasuse : false
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:31
,D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:7:31
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@15d1cbb on behalf of 3328
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3328): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3328): in trimDatabase
V/DownloadManager( 3328): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@270865d8 on behalf of 3328
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LGDMClient( 4197): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3328): DownloadService onStartCommand
V/DownloadManager( 3328): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = mtalk.google.com, class = 1, type = 1
V/DownloadManager( 3328): created cursor android.database.sqlite.SQLiteCursor@2536c997 on behalf of 3328
V/DownloadManager( 3328): processing inserted download 1
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3328): processing inserted download 4
V/DownloadManager( 3328): processing inserted download 7
E/LGDMClient( 4197): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4197): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3328): processing inserted download 8
D/LGDMClient( 4197): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3328): processing inserted download 9
V/DownloadManager( 3328): processing inserted download 10
V/DownloadManager( 3328): processing inserted download 16
,V/DownloadManager( 3328): processing inserted download 17
V/DownloadManager( 3328): processing inserted download 18
V/DownloadManager( 3328): processing inserted download 21
V/DownloadManager( 3328): processing inserted download 22
I/iu.Environment( 2369): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2369): num queued entries: 0
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/iu.UploadsManager( 2369): num updated entries: 0
I/iu.SyncManager( 2369): NEXT; no task
,V/DownloadManager( 3328): DownloadService onDestroy
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  317): res_queryN name = mtalk.google.com succeed
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 6870): Starting books sync
D/BooksSync( 6870): started syncMyEbooks
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com succeed
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2369): [AccountUtils] Account not ready
W/Kids    ( 2369): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2369): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2369): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2369): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2369): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2369): 	at java.lang.Thread.run(Thread.java:818)
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
V/FormManager( 6947): There are no updated forms. The schedule will be deleted.
V/FormManager( 6947): Alarm would be updated, because LastCheckTime has been updated.
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  317): res_queryN name = www.googleapis.com succeed
,D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3066521396634220669&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = www.google.com succeed
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1042): isHttpConnectionAvailable - We got a valid response : 204
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3066521396634220669&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2145): Explicit concurrent mark sweep GC freed 59433(3MB) AllocSpace objects, 26(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.292ms total 72.851ms
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3066521396634220669&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3066521396634220669&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
,E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3066521396634220669&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215818, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 237807653090; DSPS: 7933165; Offset : -4308039940
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{349f26d4 type 2 when 241705 android} when 241705
,I/jxcore-log( 6655): TAP version 13
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # multiplex can send data
I/jxcore-log( 6655): 
I/jxcore-log( 6655): got: setup_multiplex can send data
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_multiplex can send data_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 1 String should be length:200
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # enqueue and run in order
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_enqueue and run in order
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_enqueue and run in order_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 2 firstPromise setTimeout
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 3 firstPromise result
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 4 firstPromise testValue
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 5 secondPromise setTimeout
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 6 secondPromise result
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 7 secondPromise testValue
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 8 thirdPromise in promise
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 9 thirdPromise result
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 10 thirdPromise testValue
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # basic
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_basic
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_basic_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 11 sane
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # another
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_another
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_another_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/jxcore-log( 6655): ok 12 sane
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_successfully create a new pkcs12 file and return hash value_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 257820180635; DSPS: 8588936; Offset : -4308055223
,I/jxcore-log( 6655): ok 13 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 14 null
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 15 (unnamed assert)
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 16 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 17 should not throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_successfully read a previous pkcs12 file and return hash value_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 18 (unnamed assert)
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 19 (unnamed assert)
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 20 should not throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 21 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 22 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ack: setup_failed to extract public key because of corrupt pkcs12 file_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 23 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # failed to get mobile documents path
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_failed to get mobile documents path
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ack: setup_failed to get mobile documents path_ok
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 24 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#init should register the peerAvailabilityChanged event
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#init should register the peerAvailabilityChanged event_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 25 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 26 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 27 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #init should register the networkChanged event
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#init should register the networkChanged event
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#init should register the networkChanged event_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 28 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should throw on null device name
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on null device name
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on null device name_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 29 should throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on empty string device name
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on empty string device name_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 30 should throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on non-number port
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on non-number port_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 31 should throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on NaN port
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on NaN port_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 32 should throw
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # #startBroadcasting should throw on negative port
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on negative port
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on negative port_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 33 should throw
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # #startBroadcasting should throw on too large port
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should throw on too large port
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should throw on too large port_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 34 should throw
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 35 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 36 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 37 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 38 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 39 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 40 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 41 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 42 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 43 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 44 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 45 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 46 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 47 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_#connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_#connect should call Mobile("Connect") and handle an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 48 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 49 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_should call Mobile("Disconnect") without an error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_should call Mobile("Disconnect") without an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 50 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 51 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ack: setup_should call Mobile("Disconnect") and handle an error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ok 52 should be equal
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): ok 53 should be equal
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok
I/jxcore-log( 6655): 
,I/jxcore-log( 6655): # teardown
I/jxcore-log( 6655): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b0a17df added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282852.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591282852.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282852.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3760): [BTUI] createSocketChannel FD=84 mFd=82
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591282852.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591282852.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591282852.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6b6370ea target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6b6370ea target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
,D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238323835322e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238323835322e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323835321f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323835321f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2674): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1982): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1042): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282852.6655, mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/jxcore-log( 6655): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323835321f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323835321f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=91 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6655): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52252fb added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282987.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591282987.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282987.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591282987.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591282987.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591282987.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9dc72e98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9dc72e98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238323938372e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238323938372e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323938371f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323938371f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591282987.6655, mode: WIFI
I/jxcore-log( 6655): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=92 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1042): InactiveState{ when=-2ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=93 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6655): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323938371f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238323938371f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000,, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b923d7 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283044.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283044.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283044.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283044.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283044.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283044.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@66052276 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@66052276 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333034342e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283044.6655, mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333034342e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333034341f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333034341f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/jxcore-log( 6655): ok 58 Should be able to call startBroadcastin,g without error
I/jxcore-log( 6655): 
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333034341f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333034341f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
,D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6655): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-4ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34822673 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283096.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283096.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283096.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283096.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283096.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283096.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c1186da8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c1186da8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333039362e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333039362e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333039361f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333039361f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283096.6655, mode: WIFI
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6655): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDisco,verer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=97 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333039361f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333039361f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6655): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
V/org.thaliproject.p2p.,btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ceb6cf added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283153.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0,
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283153.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283153.6655, mode: WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283153.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283153.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283153.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46e14534 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46e14534 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333135332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333135332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333135331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333135331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283153.6655, mode: WIFI
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/jxcore-log( 6655): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p,2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333135331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333135331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1042): InactiveState{ when=-6ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
,I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6655): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
,D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa9f0eb added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283223.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283223.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283223.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283223.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283223.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283223.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@756dea38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@756dea38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333232332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333232332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333232331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333232331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283223.6655, mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6655): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333232331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333232331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
I/jxcore-log( 6655): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-FIND-STOPPED 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6,655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb4b0c7 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283291.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283291.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283291.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283291.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283291.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283291.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cb4df3ee target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cb4df3ee target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333239312e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333239312e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333239311f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333239311f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283291.6655, mode: WIFI
I/wpa_supplicant( 2674): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1982): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1042): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/LGWifiP2pService( 1042): discovery change broadcast true
I/jxcore-log( 6655): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): s,topListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333239311f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333239311f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 665,5): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
I/jxcore-log( 6655): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac19263 added. We now have 9 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283375.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283375.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283375.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283375.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283375.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283375.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4aafa8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b4aafa8 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333337352e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333337352e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333337351f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333337351f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/LGWifiP2pService( 1042): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283375.6655, mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6655): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDis,coverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333337351f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/jxcore-log( 6655): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333337351f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1042): remove client information from framework
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d30f1bf added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-5ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device, discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/LGWifiP2pService( 1042): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283433.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283433.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283433.6655, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283433.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283433.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283433.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39bfd072 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39bfd072 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333433332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333433332e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283433.6655, mode: WIFI
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333433331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333433331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true
,D/LGWifiP2pService( 1042): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
,I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6655): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1042): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333433331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,I/jxcore-log( 6655): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333433331f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6655): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1042): InactiveState{ when=-4ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b0ceadb added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6655): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283499.6655
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283499.6655","ra":"58:3F:54:73:64:C0"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6655): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283499.6655, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6655): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454591283499.6655","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: {"pi":"58:3F:54:73:64:C0","pn":"1454591283499.6655","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454591283499.6655","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c643325a target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c643325a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState add service
D/LGWifiP2pService( 1042): add a new client
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333439392e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343539313238333439392e36363535222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333439391f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK
I/io.jxcore.node.ConnectionHelper( 6655): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454591283499.6655, mode: WIFI
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiNative-p2p0( 1042): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333439391f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/jxcore-log( 6655): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 6655): 
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1042): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6655): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): shutdown
I/wpa_supplicant( 2674): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6655): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6655): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: 1 listener(s) left
,D/WifiMonitor( 1042): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6655): setState: NOT_STARTED
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=108 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1982): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiNative-p2p0( 1042): P2P_FIND 120: returned true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): start: OK,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
D/LGWifiP2pService( 1042): discovery change broadcast true,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6655): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6655): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6655): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: STARTED
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2674): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1042): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6655): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6655): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1042): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333439391f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6655): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6655): setState: NOT_STARTED
D/WifiNative-p2p0( 1042): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343539313238333439391f36363535222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1042): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 6655): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1042): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6655): Local services cleared successfully
D/WifiMonitor( 1042): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1042): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6655): P2P device discovery stopped successfully
E/WifiMonitor( 1042): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1982): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService( 1042): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6655): Service requests cleared successfully
,D/LGWifiP2pService( 1042): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): discovery change broadcast false
I/jxcore-log( 6655): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 6655): 
I/jxcore-log( 6655): # setup
I/jxcore-log( 6655): 
E/WifiStateMachine( 1042):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
E/WifiStateMachine( 1042):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
,E/WifiStateMachine( 1042):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
E/WifiStateMachine( 1042):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 4 0
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{5415419 type 2 when 271740 android} when 271740
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,I/BooksSync( 6870): Starting books sync
,D/BooksSync( 6870): started syncMyEbooks
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
,D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6983861114165479791&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,I/art     ( 1042): Explicit concurrent mark sweep GC freed 109854(5MB) AllocSpace objects, 8(768KB) LOS objects, 33% free, 44MB/67MB, paused 3.258ms total 194.825ms
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
,D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6983861114165479791&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6983861114165479791&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6983861114165479791&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818),
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
,E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6983861114165479791&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 263489, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 277822050419; DSPS: 9244357; Offset : -4308046880
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 297823821817; DSPS: 9899775; Offset : -4308045581
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{1690efbb type 2 when 302014 android} when 302014
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 317825750090; DSPS: 10555198; Offset : -4308039837
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{2a633cd8 type 2 when 337130 android} when 337130
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,I/BooksSync( 6870): Starting books sync
,D/BooksSync( 6870): started syncMyEbooks
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1423): Notification difference=198
,D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6870): null auth token
W/ApiaryClient( 6870): Error response from books API: {
,W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1514843345241953413&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
,W/ApiaryClient( 6870): gdata-version: 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 337827787323; DSPS: 11210625; Offset : -4308047151
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
,D/QuickStatusbarLayout( 1423): Notification difference=198
,D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1514843345241953413&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1514843345241953413&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1514843345241953413&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
,E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1514843345241953413&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 337130, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 357829886273; DSPS: 11866054; Offset : -4308054018
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{2a882a02 type 2 when 367263 android} when 367263
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6187): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6187): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6187): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6187): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6187): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6187): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6187): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6187): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = play.googleapis.com succeed
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 377831499079; DSPS: 12521467; Offset : -4308058644
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 397832810894; DSPS: 13176870; Offset : -4308059136
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 417834716094; DSPS: 13832292; Offset : -4308045922
,I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1042): battery changed pluggedType: 2
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1982): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1982): Battery Level Remaining: 100%
D/LEDHandler( 1982): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3760): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 437836781972; DSPS: 14487720; Offset : -4308055319
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 457838753058; DSPS: 15143144; Offset : -4308037357
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{5934914 type 2 when 463543 android} when 463543
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,I/BooksSync( 6870): Starting books sync
,D/BooksSync( 6870): started syncMyEbooks
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1397925742203002001&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1397925742203002001&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1042): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1042): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1042): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1042): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1042): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1423): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1423): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1423): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1423): handleNotificationPosted(true)
D/QuickCircle( 1423): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1423): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): post do just update job
D/LgeQuickCoverNotificationData( 1423): showAll3
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1423): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1423): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1423): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1423): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1423): updateNotificationData: count=3
,W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6870): Authentication error
E/BooksAccountManager( 6870): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6870): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6870): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6870): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6870): null auth token
D/QuickStatusbarLayout( 1423): Notification difference=198
D/QuickStatusbarLayout( 1423): child = android.widget.LinearLayout{1d4bc9f2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6870): Error response from books API: {
W/ApiaryClient( 6870):  "error": {
W/ApiaryClient( 6870):   "errors": [
W/ApiaryClient( 6870):    {
W/ApiaryClient( 6870):     "domain": "global",
W/ApiaryClient( 6870):     "reason": "required",
W/ApiaryClient( 6870):     "message": "Login Required",
W/ApiaryClient( 6870):     "locationType": "header",
W/ApiaryClient( 6870):     "location": "Authorization"
W/ApiaryClient( 6870):    }
W/ApiaryClient( 6870):   ],
W/ApiaryClient( 6870):   "code": 401,
W/ApiaryClient( 6870):   "message": "Login Required"
W/ApiaryClient( 6870):  }
W/ApiaryClient( 6870): }
,W/ApiaryClient( 6870): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1397925742203002001&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6870): Headers:
W/ApiaryClient( 6870): accept-encoding: [gzip]
W/ApiaryClient( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6870): gdata-version: 2
,E/BooksSync( 6870): Soft error: 
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1397925742203002001&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
,E/BooksSync( 6870): Sync error
E/BooksSync( 6870): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6870): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1397925742203002001&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6870): Headers:
E/BooksSync( 6870): accept-encoding: [gzip]
E/BooksSync( 6870): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6870): gdata-version: 2
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6870): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6870): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6870): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6870): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6870): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6870): {
E/BooksSync( 6870):  "error": {
E/BooksSync( 6870):   "errors": [
E/BooksSync( 6870):    {
E/BooksSync( 6870):     "domain": "global",
E/BooksSync( 6870):     "reason": "required",
E/BooksSync( 6870):     "message": "Login Required",
E/BooksSync( 6870):     "locationType": "header",
E/BooksSync( 6870):     "location": "Authorization"
E/BooksSync( 6870):    }
E/BooksSync( 6870):   ],
E/BooksSync( 6870):   "code": 401,
E/BooksSync( 6870):   "message": "Login Required"
E/BooksSync( 6870):  }
E/BooksSync( 6870): }
E/BooksSync( 6870): 
E/BooksSync( 6870): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6870): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6870): 	... 8 more
I/BooksSync( 6870): Finished books sync
D/SyncManager( 1042): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 463543, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 477841578728; DSPS: 15798597; Offset : -4308049769
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{878d25e type 2 when 493680 android} when 493680
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 497843213668; DSPS: 16454010; Offset : -4308032235
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 517845160900; DSPS: 17109434; Offset : -4308038233
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 537847104799; DSPS: 17764858; Offset : -4308047432
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 557848906613; DSPS: 18420277; Offset : -4308046077,
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=110 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1042): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1042): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1042): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=111 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1042):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=569240
E/WifiStateMachine( 1042):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=569241
E/WifiStateMachine( 1042):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=569241
E/WifiConfigStore( 1042): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1042): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1042): InitialState.processMessage what=4
D/Tethering( 1042): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1042): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1042): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1042): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1042): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/DhcpStateMachine( 1042): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  317): Clearing all IP addresses on wlan0
I/jxcore-log( 6655): Toggling radios to false
I/jxcore-log( 6655): 
,V/NativeCrypto( 2145): Read error: ssl=0xaa6d7a00: I/O error during system call, Connection timed out
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=112 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/BluetoothManagerService( 1042): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1042): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e3e663f mBinding = false
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1042): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1042): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6729): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6729): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1042): NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1042): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1982): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1042): WifiStateMachine: Leaving Connected state
D/BluetoothManagerService( 1042): Message: 2
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 111 0 rt=569411  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 111 0 rt=569412  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1042):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1042):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 112 0 rt=569416  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1042): hidePasspointNotification off =false
D/BluetoothManagerService( 1042): Sending off request.
D/LocationManagerService( 1042): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1042): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1042): JNI:system_update. Event-4
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGBluetoothServiceAdapter( 3760): [BTUI] Precleanup
,D/BluetoothAdapterState( 3760): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3760): Setting state to 13
I/BluetoothAdapterState( 3760): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3760): onBluetoothDisable()
I/BluetoothAdapterState( 3760): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1042): Message: 60
D/BluetoothManagerService( 1042): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1042): Bluetooth State Change Intent: 12 -> 13
E/WifiStateMachine( 1042):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 112 0 rt=569425  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServiceImplEx( 1042): setWifiEnabled: false pid=6655, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/WifiService( 1042): setWifiEnabled: false pid=6655, uid=10311
E/WifiService( 1042): Invoking mWifiStateMachine.setWifiEnabled
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1982): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/BluetoothMapService( 3760): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3760): STATE_TURNING_OFF
V/BtOppService( 3760): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3760): Handler(): got msg=4
D/BluetoothMapService( 3760): MAP Service closeService in
D/BluetoothMapMasInstance( 3760): MAP Service shutdown
V/BluetoothMapMasInstance( 3760): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3760): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3760): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3760): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3760): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3760): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3760): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3760): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 3760): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3760): MAP Service closeService out
I/BtOppRfcommListener( 3760): stopping Accept Thread
V/BtOppRfcommListener( 3760): close mBtServerSocket
V/BtOppRfcommListener( 3760): waiting for thread to terminate
E/BtOppRfcommListener( 3760): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3760): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3760): done waiting for thread to terminate
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1042): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1042):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,D/LocationManagerService( 1042): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1042): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1042): JNI:system_update. Event-4
E/WifiStateMachine( 1042):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1042): hidePasspointNotification off =false
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/jxcore-log( 6655): Radios toggled
I/jxcore-log( 6655): 
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService( 1042): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1042): disableDataServiceNotify
D/DSQN    ( 1042): stop dsqn bin
,E/WifiStateMachine( 1042):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1042):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1042):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1042): notifyType LOST for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1042):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1042):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1042): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1042): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1042): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1042): setSupplicantStateSCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1042): Disconnected - quitting
D/CSLegacyTypeTracker( 1042): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1042): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/BtOppService( 3760): onDestroy
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsControl( 6729): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6729): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6729): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6729): [AUTORUN] setTetherStatus() : status=false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1042): sendStickyBroadcastDelayed: delayMs=3000, action=an,droid.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1042): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1042): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1042): Removing idletimer
W/Settings( 1042): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1042): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1042): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,V/NetworkPolicy( 1042): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    ( 1042): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1042):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGWifiP2pService( 1042): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1042): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@17e31789
D/LGWifiP2pService( 1042): P2pDisablingState
D/LGWifiP2pService( 1042): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): p2p socket connection lost
D/LGWifiP2pService( 1042): P2pDisabledState
V/WfdStateTracker( 1982): WfdStateTracker handleDirectStateChangedEvent: 0
E/WifiStateMachine( 1042):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WfdsService( 1982): WifiP2pState is changed : false
D/WifiNative-wlan0( 1042): doBoolean: DRIVER BTCOEXMODE 2
D/WfdsService( 1982): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1982): Set the WFDS Monitor: false
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/LGWifiP2pService( 1042): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1042): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java( 1042): Sending msg: 4 arg1:0 arg2:1
D/WifiScanningService( 1042): SCAN_AVAILABLE : 1
D/RttService( 1042): SCAN_AVAILABLE : 1
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/WfdsMonitor( 1982): WFDS Monitor is stopped
D/LocSvc_java( 1042): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1042): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/WfdsService( 1982): STATE : WfdsDisabledState - enter
D/LocSvc_java( 1042): ignore wifi update if we are not in OPENING or CLOSING
D/CtrlSupplicant( 1982): Received on exit socket, terminate
E/CtrlSupplicant( 1982): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1982): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1982): WfdsMonitorThread is received the interrupt - closing
D/WifiScanningService( 1042): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1042): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1042): doBoolean: SET ps 1
D/RttService( 1042): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsSession:Controller( 1982): DefaultState - msg [9441355] is not handled
W/WfdsService( 1982): DefaultState - msg [9445378] is not handled
D/WifiNative-wlan0( 1042): SET ps 1: returned true
D/CommandListener(  317): Clearing all IP addresses on wlan0
D/WifiNative-p2p0( 1042): doBoolean: TERMINATE
D/WifiNative-p2p0( 1042): TERMINATE: returned true
E/WifiStateMachine( 1042): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1042): useWiFiOffloading() : false
E/WifiStateMachine( 1042): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( ,1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1042): hidePasspointNotification off =false
W/Settings( 1042): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1042): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1042): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1982): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1042): WIFI_STATE_CHANGED_ACTION [0]
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1042): StoppedState
D/DhcpStateMachine( 1042): StoppedState{ when=-42ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1042):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1042):  DefaultState CMD_ON_QUIT 0 0
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 1042): Explicit concurrent mark sweep GC freed 58502(2MB) AllocSpace objects, 12(1344KB) LOS objects, 33% free, 44MB/66MB, paused 1.537ms total 243.185ms
D/BluetoothAdapterProperties( 3760): Scan Mode:20
D/BluetoothAdapterState( 3760): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothSapService( 3760): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3760): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothPbapService( 3760): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3760): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3760): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,D/LGBluetoothOppAdapter( 3760): [BTUI] LGBluetoothOppAdapter cleanup
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0019
V/BluetoothPbapReceiver( 3760): PbapReceiver onReceive 
W/bt-l2cap( 3760): L2CAP - PSM: 0x0019 not found for deregistration
V/BluetoothPbapReceiver( 3760): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0017
V/BluetoothPbapReceiver( 3760): ***********state = 13
W/bt-l2cap( 3760): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3760): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3760): bta_gattc_deregister Deregister Failedm unknown client cif
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaa6d7a00: I/O error during system call, Broken pipe
V/BluetoothPbapReceiver( 3760): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3760): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3760): state: 13
V/BluetoothPbapService( 3760): Pbap Service closeService in
V/BluetoothPbapService( 3760): successfully stopped pbap service
V/BluetoothPbapService( 3760): Pbap Service closeService out
V/BluetoothPbapService( 3760): Pbap Service onDestroy
V/BluetoothPbapService( 3760): Pbap Service closeService in
V/BluetoothPbapService( 3760): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3760): [BTUI] cleanup
W/ContextImpl( 6729): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1042): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7896 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/BluetoothManagerService( 1042): Message: 20
D/BluetoothManagerService( 1042): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28fbb66a:true
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothManagerService( 1042): Message: 30
,D/BluetoothManagerService( 1042): Message: 30
D/LocalBluetoothProfileManager( 6729): Adding local MAP profile
D/BluetoothMap( 6729): Create BluetoothMap proxy object
D/BluetoothManagerService( 1042): Message: 30
D/BluetoothManagerService( 1042): Message: 30
D/LocalBluetoothProfileManager( 6729): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6729):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 6729): [BTUI] initUserBindClient
W/ContextImpl( 6729): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6729): finishStartingService: stopping service
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/BluetoothInputDevice( 6729): Proxy object connected
D/HidProfile( 6729): Bluetooth service connected
D/BluetoothPan( 6729): BluetoothPAN Proxy object connected
D/PanProfile( 6729): Bluetooth service connected
D/BluetoothMap( 6729): Proxy object connected
D/MapProfile( 6729): Bluetooth service connected
D/BluetoothMap( 6729): getConnectedDevices()
D/BluetoothMap( 6729): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6729): [BTUI] onServiceConnected
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/ActivityThread( 7896): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7896): No ProfileInfo entries
I/LG Account v2.2( 7896): isEnabled: false
I/Feature ( 7896): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7896): [Lifetracker]Country: EU
I/Feature ( 7896): [Lifetracker]Operator: OPEN
I/Feature ( 7896): [Lifetracker]Ranking support: false
I/Feature ( 7896): [Lifetracker]Comfort support: false
I/Feature ( 7896): [Lifetracker]Accessory: true
I/Feature ( 7896): [Lifetracker]Health device: true
I/Feature ( 7896): [Lifetracker]Extra Pedometer: false
I/Feature ( 7896): [Lifetracker]Blood glucose device: false
I/Feature ( 7896): [Lifetracker]Device Number: 3
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/LGBluetoothAuthorization( 6729): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 6729): onReceive
D/LGBluetoothAuthorization( 6729): [BTUI] cancel All Notification
,I/ActivityManager( 1042): Killing 2215:com.lge.music/u0a34 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6729): return without doing reset settings.
V/AudioFlinger(  322): 2215 died, releasing its sessions
V/AudioFlinger(  322):  pid 1876 @ 0
,V/AudioFlinger(  322):  pid 3257 @ 1
V/AudioFlinger(  322):  pid 3257 @ 2
,V/BluetoothOppReceiver( 3760): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3760): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3760): [BTUI] cancel opp active transfer file notification
,W/libprocessgroup( 1042): failed to open /acct/uid_10034/pid_2215/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 3760): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3760): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3760): Ftp Service onStartCommand
V/BluetoothFtpService( 3760): action: android.bluetooth.adapter.action.STATE_CHANGED
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/BluetoothFtpService( 3760): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3760): Shutdown
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3760): successfully stopped ftp service
,V/BluetoothSapReceiver( 3760): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3760): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3760): SapReceiver onReceive 
V/BluetoothSapReceiver( 3760): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3760):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3760): Calling SAP service start service with action = null
V/BluetoothFtpService( 3760): Ftp Service onDestroy
V/BluetoothFtpService( 3760): Ftp Service closeService
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1042): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7924 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3760): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3760): state: 13
V/BluetoothSapService( 3760): Stopping SAP server process
V/BluetoothSapService( 3760): Sap Service closeSapService in
V/BluetoothSapService( 3760): Close listen Socket : 
V/BluetoothSapService( 3760): Close rfcomm Socket : 
V/BluetoothSapService( 3760): Close sapd  Socket : 
,V/BluetoothSapService( 3760): Sap Service closeSapService out
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothSapService( 3760): Sap Service onDestroy
,V/BluetoothSapService( 3760): Sap Service closeSapService in
V/BluetoothSapService( 3760): Close listen Socket : 
V/BluetoothSapService( 3760): Close rfcomm Socket : 
V/BluetoothSapService( 3760): Close sapd  Socket : 
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothSapService( 3760): Sap Service closeSapService out
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
W/ResourcesManager( 7924): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2145): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6752): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
,D/QRemote ( 6776): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6776): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6776): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6947): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
V/FormManager( 6947): Network unavailable.
,V/FormManager( 6947): Network unavailable.
,I/ActivityManager( 1042): Killing 6187:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1042): failed to open /acct/uid_10044/pid_6187/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3760): cleanup
,I/bt_lpm  ( 3760): LPM is already off!!!
I/bt_userial_mct( 3760): exiting userial_read_thread
D/bt_userial_mct( 3760): Leaving userial_evt_read_thread()
W/bt-btif ( 3760): ag scb idx 1 not allocated
E/bt-btif ( 3760): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3760): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3760): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3760): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3760): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3760): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3760): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3760): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3760): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3760): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3760): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3760): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3760): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3760): hw_epilog_process
D/bt_hci_bdroid( 3760): cleanup Finalizing cleanup
D/bt_userial_mct( 3760): userial_close
E/bt_userial_mct( 3760): pthread_join() FAILED result:3
I/bt_vendor( 3760): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3760): set_power 0
I/bt_vendor( 3760): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3760): bluetooth satus is on
I/bt_vendor( 3760): bt-vendor : resetting BT status
I/bt_vendor( 3760): Starting hciattach daemon
I/bt_vendor( 3760): try to set false
,I/bt_vendor( 3760): Starting hciattach daemon
I/bt_vendor( 3760): try to set false
I/bt_vendor( 3760): cleanup
I/GKI_LINUX( 3760): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3760): GKI_exit_task 0 done
I/GKI_LINUX( 3760): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3760): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3760): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3760): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3760): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
D/HeadsetStateMachine( 3760): Exit Disconnected: -1
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1042): Proxy object disconnected
D/AudioService( 1042): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 3760): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3760): Exit Disconnected: -1
D/BluetoothAdapterState( 3760): Stopping profile services that were post enabled
D/LGBluetoothAvrcpQcomAdapter( 3760): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3760): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3760): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
D/BluetoothA2dp( 1042): Proxy object disconnected
D/AudioService( 1042): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3760): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
D/HealthService( 3760): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
,D/PanService( 3760): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
D/HeadsetStateMachine( 3760): Unbinding service...
D/HeadsetPhoneState( 3760): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3760): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3760): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3760): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3760): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3760): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3760): [BTUI] LGBluetoothHfpAdapter cleanup
D/BtGatt.DebugUtils( 3760): handleDebugAction() action=null
D/BtGatt.GattService( 3760): Received stop request...Stopping profile...
D/BtGatt.GattService( 3760): stop()
D/BtGatt.AdvertiseManager( 3760): advertise clients cleared
,D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
D/BluetoothMapService( 3760): Received stop request...Stopping profile...
D/BluetoothMapService( 3760): stop()
D/BluetoothMapEmailAppObserver( 3760): deinitObservers()
D/BluetoothMapEmailAppObserver( 3760): removeReceiver()
D/BluetoothAdapterService( 3760): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee47cfb
I/BluetoothA2dpServiceJni( 3760): cleanupNative
I/GKI_LINUX( 3760): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3760): GKI_exit_task 2 done
I/GKI_LINUX( 3760): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3760): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3760): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3760): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3760): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3760): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3760): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3760): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3760): Handler(): got msg=4
D/BluetoothMapService( 3760): MAP Service closeService in
D/LGBluetoothMapAdapter( 3760): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3760): MAP Service closeService out
D/BluetoothAdapterState( 3760): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3760): Setting state to 10
I/BluetoothAdapterState( 3760): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3760): cleanup()
D/BluetoothMapService( 3760): MAP Service closeService in
D/LGBluetoothMapAdapter( 3760): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3760): MAP Service closeService out
D/BluetoothManagerService( 1042): Message: 60
D/BluetoothManagerService( 1042): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1042): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3760): Entering OffState
D/BluetoothInputDevice( 6729): onBluetoothStateChange: up=false
D/BluetoothMap( 6729): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
D/BluetoothPan( 6729): onBluetoothStateChange on: false
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1042): onBluetoothStateChange: up=false
D/BluetoothPbap( 6729): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1042): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1042): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1042): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1042): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1042): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1042): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e3e663f mBinding = false
D/BluetoothManagerService( 1042): Sending unbind request.
I/GKI_LINUX( 3760): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3760): GKI_exit_task 1 done
I/GKI_LINUX( 3760): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3760): cleanupNative: return from cleanup
I/art     ( 3760): --- WEIRD: removing null entry 246
W/art     ( 3760): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3760): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3760): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1042): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3760): System.exit called, status: 0
I/AndroidRuntime( 3760): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  322): 3760 died, releasing its sessions
V/AudioFlinger(  322):  pid 1876 @ 0
V/AudioFlinger(  322):  pid 3257 @ 1
V/AudioFlinger(  322):  pid 3257 @ 2
,D/LGBluetoothAPIService( 1982): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1982): Message: 101
E/LGBluetoothAPIService( 1982): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1982): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1982): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 6729): [BTUI] onServiceDisconnected
I/ActivityManager( 1042): Process com.android.bluetooth (pid 3760) has died
W/ActivityManager( 1042): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1042): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 11000ms
,D/LGBluetoothAPIService( 1982): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1982): Message: 2
D/LGBluetoothAPIService( 1982): unbindAndFinish(): null mBinding = false
D/LGBluetoothFeatureConfig( 6729): isPrivacyLogsEnabled : true
,E/LGBluetoothEventManager( 6729): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6729): [BTUI] clear device connection state
D/BluetoothAdapter( 1464): 375391277: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1464): 375391277: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 6729): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1042): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7971 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 6729): finishStartingService: stopping service
,I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 18.722ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 273us total 14.391ms
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 13.308ms
,W/ResourcesManager( 7971): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7971): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7971): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7971): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7971): Loading JNI Library
,D/BluetoothAdapterApp( 7971): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e39d200 Instance Count = 1
,D/BluetoothAdapterApp( 7971): onCreate
D/ProfileConfigQcom( 7971): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7971): Adding HeadsetService
D/ProfileConfigQcom( 7971): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7971): Adding A2dpService
D/ProfileConfigQcom( 7971): [BTUI] HidService is supported
,D/ProfileConfigQcom( 7971): Adding HidService
D/ProfileConfigQcom( 7971): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7971): Adding HealthService
D/LGBluetoothFeatureConfig( 7971): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7971): [BTUI] PanService is supported
D/ProfileConfigQcom( 7971): Adding PanService
D/ProfileConfigQcom( 7971): [BTUI] GattService is supported
D/ProfileConfigQcom( 7971): Adding GattService
D/ProfileConfigQcom( 7971): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7971): Adding BluetoothMapService
D/ProfileConfigQcom( 7971): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7971): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7971): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7971): ***********state = 10
V/LGMDMManagerInternal( 7971): Create singleton instance
D/LGBluetoothAPIServer( 7971): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7971): [BTUI] onBind()
D/LGBluetoothAPIService( 1982): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1982): Message: 100
D/LGBluetoothAPIService( 1982): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LGBluetoothUserBindClient( 6729): [BTUI] onServiceConnected
,D/BluetoothPermissionRequest( 6729): onReceive
D/LGBluetoothUtils( 6729): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6729): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 6729): return without doing reset settings.
D/LGBluetoothOppAdapter( 7971): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7971): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7971): [BTUI] checkServiceStart
,V/BluetoothSapReceiver( 7971): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 7971): SapReceiver onReceive ,
V/BluetoothSapReceiver( 7971): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7971):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7924): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2145): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2674): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2674): monitor socket send errors count : 1
I/wpa_supplicant( 2674): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1982-2\x00 that cannot receive messages
,W/wpa_supplicant( 2674): USIM:  scard_deinit function
D/WifiMonitor( 1042): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1042): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=114 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1042):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 114 0 rt=571439  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1042):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 114 0 rt=571440  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1042): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1042): WifiMonitor:wlan0 cnt=115 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1042): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1042):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 115 0
,D/WfdsService( 1982): Supplicant Connection state is changed : false
D/WfdsService( 1982): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1982): Set the WFDS Monitor: false
D/WfdsMonitor( 1982): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1042): stopMonitoring
E/WifiStateMachine( 1042): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1042): useWiFiOffloading() : false
E/WifiStateMachine( 1042): CONFIG_LGE_WLAN_PATH : true
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/WifiServerServiceExt( 1042): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1042): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1042): batteryPsActivateMsgHandler : this is not treated
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1982): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 6752): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 6752): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6752): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6729): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6729): MCCMNC not supported: null
D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 6947): Network unavailable.
,W/FormManager( 6947): Network not available. Please check & try again.
,V/FormManager( 6947): Network unavailable.
D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1042): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1042): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1042): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5425): type=WIFI subType= reason=null isConnected=false
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6887): onReceive
D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
,D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:13:15
,D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:13:15
D/GpsLocationProvider( 1042): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/FormManager( 6947): Network not available. Please check & try again.
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1042): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/FormManager( 6947): Network unavailable.
I/iu.Environment( 2369): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 2369): num queued entries: 0
I/iu.UploadsManager( 2369): num updated entries: 0
I/iu.SyncManager( 2369): NEXT; no task
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 6947): Network unavailable.
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 4925): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6887): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6887): onReceive
,D/AppUp4:CustFacade( 6887): Context : android.app.ReceiverRestrictedContext@36ba5e8a
D/AppUp4:CustFacade( 6887): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6887): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6887): begin check event
I/AppUp4:CustModeStarterReceiver( 6887): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 6915): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 6915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 6947): Network not available. Please check & try again.
I/LgeMiscReceiver( 3257): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3257): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3257): networkInfo.isConnected() = false
D/WeatherAncestor( 7031): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:13:15
,D/Weather.Utils( 7031): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7031): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7031): 2 : This is isUpdating : false
D/WeatherAncestor( 7031): connectivity changed - connection : true
D/WeatherService( 7031): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a7fe118
V/FormManager( 6947): Network unavailable.
D/ForecastDataCache( 7031): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7031): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7031): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7031): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7031): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:13:15
V/FormManager( 6947): Network unavailable.
D/ChimeraCfgMgr( 2369): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LGWifiP2pService( 1042): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1042): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1042):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1042):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{2d48fb9c type 2 when 577301 com.google.android.gms} when 577301
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1042): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 577851072440; DSPS: 19075708; Offset : -4308046946
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 597852923995; DSPS: 19731129; Offset : -4308057067
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 617854938518; DSPS: 20386555; Offset : -4308056679
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 637857089864; DSPS: 21041985; Offset : -4308041641
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
,I/ActivityManager( 1042): Killing 6870:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1042): failed to open /acct/uid_10054/pid_6870/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 657859048919; DSPS: 21697409; Offset : -4308035686
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 677861285214; DSPS: 22352843; Offset : -4308057822
,D/PowerManagerServiceEx( 1042): acquireWakeLockInternal: lock=596505983, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
,I/ActivityManager( 1042): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8064 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1042): battery changed pluggedType: 2
D/LEDHandler( 1982): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1982): Battery Level Remaining: 100%
D/LEDHandler( 1982): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/DigitalAppWidgetProvider( 8064): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8064): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@361da1df
,D/PowerManagerServiceEx( 1042): releaseWakeLockInternal: lock=596505983 [*alarm*], flags=0x0
I/ActivityManager( 1042): Killing 6799:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6776): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6776): android.os.DeadObjectException
W/System.err( 6776): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6776): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6776): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6776): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6776): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6776): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6776): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6776): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6776): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6776): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6776): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6776): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6776): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6776): android.os.DeadObjectException
W/System.err( 6776): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6776): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6776): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6776): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6776): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6776): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6776): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6776): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6776): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6776): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6776): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6776): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6776): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6776): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1042): failed to open /acct/uid_1000/pid_6799/cgroup.procs: No such file or directory
W/ActivityManager( 1042): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6776): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6776): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1042): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8100 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6776): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8100): Quickset Services start...
,I/UEI.SmartControl( 8100): Manufacture = LGE
D/UEI.SmartControl( 8100): Id = LGNevo
D/UEI.SmartControl( 8100): File observer start...
E/UEI.SmartControl( 8100): IR Port is disabled: false
D/UEI.SmartControl( 8100): Starting file observer...
D/UEI.SmartControl( 8100): Extracting JNI libs...
D/UEI.SmartControl( 8100): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8100): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8100): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8100): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8100): --- Selecting new region: 6
,I/UEI.SmartControl( 8100): Model = LG-D855
D/UEI.SmartControl( 8100): QS Service created
I/UEI.SmartControl( 8100): Service initServices...
,D/UEI.SmartControl( 8100): QS start get config
D/UEI.SmartControl( 8100): Loading JNI Libs...
,I/UEI.SmartControl( 8100): Supports setup maps: true
,D/UEI.SmartControl( 8100): QS start statue = true Error code = 0
I/UEI.SmartControl( 8100): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8100): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8100): ### init IR Blaster...
D/serial_port( 8100): Configuring serial port
E/UEI.SmartControl( 8100): UEIBLaster setting for 616
I/UEI.SmartControl( 8100): Setting serial record hearder size = 2
I/UEI.SmartControl( 8100): configuring settings for MAXQ616
I/UEI.SmartControl( 8100): Get version...
,D/UEI.SmartControl( 8100): serial port data available: 21
,D/UEI.SmartControl( 8100): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 8100): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8100): QS saving settings...
,D/UEI.SmartControl( 8100): IR Blaster version: 25672567
D/UEI.SmartControl( 8100): serial port data available: 4
,I/UEI.SmartControl( 8100): Device manager: loading config....
,D/UEI.SmartControl( 8100): ----------- loading internal config...
W/ContextImpl( 8100): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 8100): Services init done
D/UEI.SmartControl( 8100): QS Service init finished
D/UEI.SmartControl( 8100): QS Service version name: 2.1.91
D/UEI.SmartControl( 8100): QS Service version code: 201091
D/UEI.SmartControl( 8100): Service requested: Control
E/UEI.SmartControl( 8100): Loading SETTINGS...
,D/UEI.SmartControl( 8100): Request IControl service: devices are loaded...
I/ActivityManager( 1042): Killing 6776:com.lge.qremote/u0a112 (adj 15): empty #17
I/QRemote ( 6776): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 8100): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 8100): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8100): -----service ready thread exits
,W/libprocessgroup( 1042): failed to open /acct/uid_10112/pid_6776/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8100): Internal service binding...
,D/UEI.SmartControl( 8100): Internal timer expired: 1
,D/UEI.SmartControl( 8100): unbind internal service
,D/UEI.SmartControl( 8100): Service.onUnbind: IControl
D/UEI.SmartControl( 8100): Service.onDestroy
D/UEI.SmartControl( 8100): Lock is in USE false
D/UEI.SmartControl( 8100): unbind internal service
W/System.err( 8100): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@30e7d956
W/System.err( 8100): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8100): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 8100): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8100): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8100): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8100): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8100): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 8100): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8100): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8100): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8100): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8100): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8100): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8100): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8100): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8100): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@30e7d956
,D/serial_port( 8100): close(fd = 25)
,I/UEI.SmartControl( 8100): Serial port is closed.
,I/UEI.SmartControl( 8100): Serial port is closed.
I/UEI.SmartControl( 8100): Serial port is closed.
,D/UEI.SmartControl( 8100): Blaster closed
D/UEI.SmartControl( 8100): Shut down QS...
,D/UEI.SmartControl( 8100): Stopping QS lib
,D/UEI.SmartControl( 8100): QS lib stop result = true
D/UEI.SmartControl( 8100): Stopped QS lib,
D/UEI.SmartControl( 8100): Stopped file observer...
D/UEI.SmartControl( 8100): QS shutdown complete
D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 697863451404; DSPS: 23008274; Offset : -4308058302
,V/AlarmManager( 1042): ELAPSED_WAKEUP set : Alarm{15f9e107 type 2 when 713261 android} when 713261
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 717865366657; DSPS: 23663696; Offset : -4308034956
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 737867349357; DSPS: 24319121; Offset : -4308036080
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 757869105912; DSPS: 24974539; Offset : -4308049337
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 777874064811; DSPS: 25630061; Offset : -4308034338
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 797876102355; DSPS: 26285488; Offset : -4308041628
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 817878009067; DSPS: 26940911; Offset : -4308057471
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 837879604215; DSPS: 27596323; Offset : -4308049394
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 857883055510; DSPS: 28251796; Offset : -4308046507
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 877885028888; DSPS: 28907221; Offset : -4308056720
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 897886937942; DSPS: 29562643; Offset : -4308039780
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 917888738872; DSPS: 30218062; Offset : -4308039363,
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 937891303709; DSPS: 30873506; Offset : -4308038184
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 957893423544; DSPS: 31528936; Offset : -4308054423
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 977895236245; DSPS: 32184355; Offset : -4308042103
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 997897752331; DSPS: 32839798; Offset : -4308059081
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1017899810188; DSPS: 33495225; Offset : -4308045979
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1037902513723; DSPS: 34150674; Offset : -4308058482
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1057904338819; DSPS: 34806093; Offset : -4308033897
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1077906282925; DSPS: 35461517; Offset : -4308042917
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1097908446720; DSPS: 36116948; Offset : -4308045896
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1117911085463; DSPS: 36772395; Offset : -4308062156
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1137912934518; DSPS: 37427815; Offset : -4308044208
,I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,D/LEDHandler( 1982): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1982): Battery Level Remaining: 100%
D/LEDHandler( 1982): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
,I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1042): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged(),
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1157914916697; DSPS: 38083240; Offset : -4308045620,
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1177916967054; DSPS: 38738667; Offset : -4308039914
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1197918975744; DSPS: 39394093; Offset : -4308045515
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1217920840477; DSPS: 40049514; Offset : -4308042380
,I/UsageStatsService( 1042): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1237922936979; DSPS: 40704943; Offset : -4308051564
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1257924903743; DSPS: 41360367; Offset : -4308037848
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1277926893214; DSPS: 42015792; Offset : -4308032018
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1042): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1042): tsOffsetIs: Apps: 1297928732321; DSPS: 42671213; Offset : -4308054536
,TIME-OUT KILL (timeout was 1200000ms)
```
