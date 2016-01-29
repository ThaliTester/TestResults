#### Test 5761781115ba656_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
W/MainApplication( 6686): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/AndroidRuntime( 6927): 
D/AndroidRuntime( 6927): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6927): CheckJNI is OFF
D/AndroidRuntime( 6927): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1954): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{35a2a208 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{35a2a208 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6942 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6927): Shutting down VM
I/art     (  348): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.388ms total 40.940ms
V/ActivityManager( 1038): Display changed displayId=0
I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 20.775ms
D/DSDPConnection( 1859): Display #0 changed.
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 19.450ms
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{1cd8b108 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{26400a1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6942): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6942): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6942): Loading: webviewchromium
,I/LibraryLoader( 6942): Time to load native libraries: 4 ms (timestamps 1648-1652)
I/LibraryLoader( 6942): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6942): Binding Chromium to main looper Looper (main, tid 1) {3a2562b8}
,I/LibraryLoader( 6942): Expected native library version number "",actual native library version number ""
I/chromium( 6942): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6942): Initializing chromium process, renderers=0
,W/art     ( 6942): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  326): registerClient() client 0xb57bbda0, uid 10311
,D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93f6e52:true
W/chromium( 6942): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6942): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6942): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6942): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6942): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6942): Build Date: 12/12/14 금
I/Adreno-EGL( 6942): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6942): Remote Branch: 
I/Adreno-EGL( 6942): Local Patches: 
I/Adreno-EGL( 6942): Reconstruct Branch: 
,W/chromium( 6942): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6942): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6942): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6942): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6942): CordovaWebView is running on device made by: LGE
,W/art     ( 6942): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6942): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6942): Render dirty regions requested: true
I/OpenGLRenderer( 6942): Initialized EGL, version 1.4
D/OpenGLRenderer( 6942): Enabling debug mode 0
,D/Atlas   ( 6942): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{33d35c7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1459): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5c2fbb8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6942): LgDataFeature() Constructor: none
D/LgDataFeature( 6942): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +558ms (total +694ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3dcd9da1 u0 com.test.thalitest/.MainActivity t4} time:252056
I/Timeline( 6942): Timeline: Activity_idle id: android.os.BinderProxy@2812e9e8 time:252057
D/JsMessageQueue( 6942): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6942): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6942): 
,D/jxcore_app_log( 6942): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434986752
,I/chromium( 6942): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6942): 
,I/chromium( 6942): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
W/jxcore-log( 6942): Initializing JXcore engine
W/jxcore-log( 6942): JXcore engine is ready
,W/Thread-789( 7017): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8480]" dev="sockfs" ino=8480 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-789( 7017): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-789( 7017): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8599]" dev="sockfs" ino=8599 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-789( 7017): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-789( 7017): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32552]" dev="sockfs" ino=32552 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6942): Starting JXcore engine
W/jxcore-log( 6942): Platform android
W/jxcore-log( 6942): 
W/jxcore-log( 6942): Process ARCH arm
W/jxcore-log( 6942): 
,I/jxcore-log( 6942): JXcore Cordova bridge is ready!
I/jxcore-log( 6942): 
W/jxcore-log( 6942): JXcore engine is started
I/jxcore-log( 6942): Toggling radios to true
I/jxcore-log( 6942): 
D/BluetoothAdapter( 6942): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=6942, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=6942, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=6942, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1038): reconnect pid=6942, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6942): Radios toggled
I/jxcore-log( 6942): 
E/WifiNative: ( 1038): [254,767,752 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
I/jxcore-log( 6942): My device name is: LGE-LG-D855
I/jxcore-log( 6942): 
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  322): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2117): Read error: ssl=0xaf49a600: I/O error during system call, Connection timed out
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7020 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2117): SSL shutdown failed: ssl=0xaf49a600: I/O error during system call, Broken pipe
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1954): handleWifiStateChangedEvent: 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [254,904,656 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=254907
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=254907
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  322): Clearing all IP addresses on wlan0
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): Dns fail occured do internet check.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=254945  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=254945  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
W/ResourcesManager( 7020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=254951  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7020): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=0
D/WifiHS20( 1038): hidePasspointNotification off =false
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=254954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/DSQN    ( 1038): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1038): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiDataContinuityService( 1038): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524292
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiServiceExtension( 1954): isInternetCheckAvailable return false
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7020): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7020): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7020): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7020): [AUTORUN] setTetherStatus() : status=false
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-181ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7060 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6061:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6061/cgroup.procs: No such file or directory
I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7060): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7020): LgDataFeature() Constructor: none
D/LgDataFeature( 7020): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
,I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7084 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1038): Killing 6515:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6515/cgroup.procs: No such file or directory
,W/ResourcesManager( 7084): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7084): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7084): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7084): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7084): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7084): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7084): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7084): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7084): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{899a3bd type 0 when 1454056316054 android} when 1454056316054
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1a7c7db2 type 2 when 255914 com.google.android.gms} when 255914
I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 7084): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7084): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7060): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7060): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7060): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7084): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7084): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7084): LgDataFeature() Constructor: none
,D/LgDataFeature( 7084): LgDataFeature() Constructor Done, null
V/SoundPool( 7084): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7084): load: fd=30, offset=10857164, length=17813, priority=1
,V/SoundPool( 7084): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 7084): doLoad: loading sample sampleID=1
I/QRemote ( 7084): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7084): Start decode
V/MediaPlayer[Native]( 7084): decode(32, 10857164, 17813)
V/MediaPlayerService(  326): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  326): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  326): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  326): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  326): player type = 3
V/AwesomePlayer(  326): AwesomePlayer create()
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): setAudioSink() 
V/AwesomePlayer(  326): reset_l() 
V/AudioCache(  326): notify(0xb5474c00, 8, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
D/Utils   (  326): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  326): setDataSource_l dataSource
V/LGParserOSAL(  326): SniffLGParser start
V/LGParserOSAL(  326): MainType:5, SubType=0
V/LGParserOSAL(  326): #### check Mime : application/ogg
V/LGParserOSAL(  326): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  326): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6603): QS Service created
D/QRemote ( 7084): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/UEI.SmartControl( 6603): Service initServices...
D/UEI.SmartControl( 6603): QS start get config
E/QRemote ( 7084): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7084): Create singleton instance
V/LGParserOSAL(  326): supported mime: application/ogg
,V/AwesomePlayer(  326): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  326): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  326): mBitrate = -1 bits/sec
V/AwesomePlayer(  326): AudioTrack Setting
V/AwesomePlayer(  326): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  326): setAudioSource() 
V/MediaPlayerService(  326): prepare
V/AwesomePlayer(  326): prepareAsync_l() 
V/MediaPlayerService(  326): wait for prepare
V/AwesomePlayer(  326): onPrepareAsyncEvent() 
V/AwesomePlayer(  326): initAudioDecoder() 
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  326): isAudioPlaybackHookOn() false
V/AwesomePlayer(  326): getUseOffload() = 0 
V/OMXCodec(  326): OMXCodec::Create
V/OMXCodec(  326): findMatchingCodecs()
V/OMXCodec(  326): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  326): matchingCodecs.size()=1
V/OMXCodec(  326): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  326): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  326): LG Codec Adapter start
V/OMXCodec(  326): OMXCodec Createtor
V/OMXCodec(  326): setComponentRole
V/OMXCodec(  326): configureCodec protected=0
V/LGCodecAdapter(  326): called getLGCodecSpecificData
V/LGCodecOSAL(  326): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMSG
V/LGCodecOSAL(  326): Not support LGCodec
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  326): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  326): Could not offload audio decode, try pcm offload
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  326): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  326): init()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  326): allocateBuffers
V/OMXCodec(  326): allocateBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  326): in,it() mAsyncCompletion wait!!! 
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  326): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  326): finishAsyncPrepare_l() 
V/AudioCache(  326): notify(0xb5474c00, 5, 0, 0)
V/AudioCache(  326): ignored
V/AudioCache(  326): notify(0xb5474c00, 1, 0, 0)
V/AudioCache(  326): prepared
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): start
V/AwesomePlayer(  326): play_l() 
V/AwesomePlayer(  326): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  326): createAudioPlayer_l
V/AwesomePlayer(  326): seekAudioIfNecessary_l() 
V/AwesomePlayer(  326): startAudioPlayer_l() 
D/AudioPlayer(  326): start of Playback, useOffload 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  326): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  326): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf6a0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  326): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  326): notify(0xb5474c00, 6, 0, 0)
V/AudioCache(  326): ignored
V/MediaPlayerService(  326): wait for playback complete
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac700000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac701000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac702000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac703000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac704000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac705000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac706000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac707000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac708000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac709000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70a000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70b000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70c000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70d000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70e000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac70f000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac710000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac711000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac712000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac713000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac714000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac715000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac716000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac717000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac718000, 0xb57c2000, 4096)
,V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac719000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71a000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71b000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71c000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71d000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71e000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac71f000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac720000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac721000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac722000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac723000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac724000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac725000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac726000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac727000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac728000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac729000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72a000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72b000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72c000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72d000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72e000, 0xb57c2000, 4096)
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac72f000, 0xb57c2000, 4096)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac730000, 0xb57c2000, 4096)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  326): write(0xb57c2000, 4096)
V/AudioCache(  326): memcpy(0xac731000, 0xb57c2000, 4096)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  326): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  326): postAudioEOS() 
V/AudioCache(  326): write(0xb57c2000, 280)
V/AudioCache(  326): memcpy(0xac732000, 0xb57c2000, 280)
V/AwesomePlayer(  326): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  326): onStreamDone
V/AwesomePlayer(  326): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  326): notify(0xb5474c00, 2, 0, 0)
V/AudioCache(  326): playback complete
V/AwesomePlayer(  326): pause_l() 
V/AudioCache(  326): notify(0xb5474c00, 7, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  326): Pause Playback at 1068125
V/AwesomePlayer(  326): reset_l() 
V/AudioCache(  326): notify(0xb5474c00, 8, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
D/AudioPlayer(  326): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf6a0 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  326): AudioPlayer releasing audio source
D/AudioPlayer(  326): AudioPlayer done releasing audio source
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): ~AwesomePlayer call
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/SoundPool( 7084): close(32)
V/SoundPool( 7084): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4691
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=2 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:191952] from screen [on:0 period:-1937596191]
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/UEI.SmartControl( 6603): Supports setup maps: true
,D/UEI.SmartControl( 6603): QS start statue = true Error code = 0
I/UEI.SmartControl( 6603): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6603): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6603): ### init IR Blaster...
D/serial_port( 6603): Configuring serial port
E/UEI.SmartControl( 6603): UEIBLaster setting for 616
I/UEI.SmartControl( 6603): Setting serial record hearder size = 2
I/UEI.SmartControl( 6603): configuring settings for MAXQ616
I/UEI.SmartControl( 6603): Get version...
D/UEI.SmartControl( 6603): serial port data available: 21
,D/UEI.SmartControl( 6603): MAXQ616 A2-X4 software.,
I/UEI.SmartControl( 6603): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6603): QS saving settings...,
D/UEI.SmartControl( 6603): IR Blaster version: 25672567
,D/UEI.SmartControl( 6603): serial port data available: 4
,W/ContextImpl( 6603): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6603): Services init done
D/UEI.SmartControl( 6603): QS Service init finished
D/UEI.SmartControl( 6603): QS Service version name: 2.1.91
D/UEI.SmartControl( 6603): QS Service version code: 201091
D/UEI.SmartControl( 6603): Service requested: Control
D/UEI.SmartControl( 6603): Internal service binding...
I/QRemote ( 7084): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6603): ------ IControl API: 11
D/UEI.SmartControl( 6603): File observer start...
E/UEI.SmartControl( 6603): IR Port is disabled: false
D/UEI.SmartControl( 6603): Starting file observer...
I/UEI.SmartControl( 6603): Registering callback...
I/UEI.SmartControl( 6603): ------ IControl API: 19
,I/UEI.SmartControl( 6603): Registering Services Ready callback...
I/UEI.SmartControl( 6603): Device manager: loading config....
D/UEI.SmartControl( 6603): ----------- loading internal config...
E/UEI.SmartControl( 6603): Loading SETTINGS...
D/UEI.SmartControl( 6603): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6603): Notify AllClients services are ready: 0
,I/QRemote ( 7084): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7084): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7084): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6603): -----service ready thread exits
D/QRemote ( 7084): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7084): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6603): ------ IControl API: 8
D/QRemote ( 7084): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7084): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7084): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7084): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7084): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7084): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7084): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7084): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7084): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7084): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7084): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454056317526]
D/QRemote ( 7084): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6335:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 7084): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6335/cgroup.procs: No such file or directory
,V/QRemote ( 7084): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7084): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 7084): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7084): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2696): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=257015  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=257035  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7084): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2696): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=257118  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=257118  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=257119
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=257119
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=257119
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=257119
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=257119
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=257120  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=257126  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/,StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
,D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2696): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=257136  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=257137  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=257138
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=257138
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
,D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7020): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7020): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7020): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7020): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7020): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  322): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=257186  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=257187  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=257187  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=257188  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=257189  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=257189  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@348d7066 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@348d7066 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  322): Setting iface cfg
D/CommandListener(  322): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1954): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  322): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadca,st for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyNetworkFactory-1( 1859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7158): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7158): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
E/DSQN    ( 7158): DSQN ssw
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7084): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7084): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7084): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7084): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7060): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7060): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7020): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7020): MCCMNC not supported: null
D/QRemote ( 7084): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7084): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7084): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7084): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7084): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7162): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7162): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7162): version 5.5.6 starting
E/dhcpcd  ( 7162): get_duid: m
D/dhcpcd  ( 7162): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7162): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7162): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7162): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7162): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7162): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7162): wlan0: sending REQUEST (xid 0xf18fd894), next in 3.99 seconds
,D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 1
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 257707345062; DSPS: 8585359; Offset : -4310565018
,D/libc-netbsd(  322): res_queryN name = clients3.google.com succeed
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LGDataListener(  322): argv[0]=dsqncommand
D/LGDataListener(  322): argv[1]=wlan0
D/LGDataListener(  322): argv[2]=1
D/LGDataListener(  322): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 08:31:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454056318932], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454056318913]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/NetworkMonitor( 5571): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5571): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7193 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7193): onCreate
W/AppUp4:DB( 7193):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7193):  setFingerPrint start
I/AppUp4:DB( 7193):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7193):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7193):  SDK version = 21
I/AppUp4:DB( 7193):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7193): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7193): onReceive
D/LgDataFeature( 7193): LgDataFeature() Constructor: none
D/LgDataFeature( 7193): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7193): Context : android.app.ReceiverRestrictedContext@130443f6
D/AppUp4:CustFacade( 7193): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7193): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7193): begin check event
I/AppUp4:CustModeStarterReceiver( 7193): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7193): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7193): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7193): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7193): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6090:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{334d96c8 type 2 when 258257 com.google.android.gms} when 258257
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6090/cgroup.procs: No such file or directory
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3351): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3351): DownloadService onCreate
I/DownloadManager( 3351): in removeSpuriousFiles
D/LGDMClient( 4203): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4203): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@3f73c6eb on behalf of 3351
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524295
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3351): in trimDatabase
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@fa97c48 on behalf of 3351
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7222 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3351): DownloadService onStartCommand
V/DownloadManager( 3351): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@2045e6c7 on behalf of 3351
V/DownloadManager( 3351): processing inserted download 1
V/DownloadManager( 3351): processing inserted download 4
V/DownloadManager( 3351): processing inserted download 7
V/DownloadManager( 3351): processing inserted download 8
V/DownloadManager( 3351): processing inserted download 9
V/DownloadManager( 3351): processing inserted download 10
V/DownloadManager( 3351): processing inserted download 16
V/DownloadManager( 3351): processing inserted download 17
V/DownloadManager( 3351): processing inserted download 18
V/DownloadManager( 3351): processing inserted download 21
V/DownloadManager( 3351): processing inserted download 22
,W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4203): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4203): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4203): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3351): DownloadService onDestroy
W/ResourcesManager( 7222): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7222): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7222): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7222): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7222): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7222): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7222): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 7222): LgDataFeature() Constructor: none
D/LgDataFeature( 7222): LgDataFeature() Constructor Done, null
D/eas_req ( 7222): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/dhcpcd  ( 7162): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7162): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7162): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7162): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7162): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7162): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7162): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7162): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7162): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7255 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 7222): JNI_OnLoad()
I/HubEmail( 7222): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7222): registerNatives()
I/HubEmail( 7222): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7222): registerNativeMethods()
I/HubEmail( 7222): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7222): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Killing 2244:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  326): 2244 died, releasing its sessions
V/AudioFlinger(  326):  pid 1859 @ 0
V/AudioFlinger(  326):  pid 3305 @ 1
V/AudioFlinger(  326):  pid 3305 @ 2
I/art     ( 1038): Explicit concurrent mark sweep GC freed 84776(3MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.436ms total 125.862ms
W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2244/cgroup.procs: No such file or directory
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3305): networkInfo.isConnected() = false
I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7301 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7321 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6546:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/libc-netbsd(  322): res_queryN name = static-avc.lglime.com succeed
W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6546/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7338 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6582:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6582/cgroup.procs: No such file or directory
,V/FormManager( 7255): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7255): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 7338): Almond Protected OAT
,I/ActivityManager( 1038): Killing 6650:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
,D/WeatherApplication( 7338): removeAccount
D/WeatherApplication( 7338): Account.length = 0
,E/WeatherApplication( 7338): OPERATOR:OPEN
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:0
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is not up-to-date, count: 0
,E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:0
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7357 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 5999:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_5999/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5571): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6942): 
I/WebViewFactory( 7357): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7357): Loading: webviewchromium
I/LibraryLoader( 7357): Time to load native libraries: 3 ms (timestamps 465-468)
I/LibraryLoader( 7357): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7357): Binding Chromium to main looper Looper (main, tid 1) {18952639}
,I/LibraryLoader( 7357): Expected native library version number "",actual native library version number ""
I/chromium( 7357): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7357): Initializing chromium process, renderers=0
W/art     ( 7357): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7357): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7357): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7357): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  326): registerClient() client 0xb57bbdc0, uid 10093
W/AudioManagerAndroid( 7357): Requires BLUETOOTH permission
I/Adreno-EGL( 7357): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7357): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7357): Build Date: 12/12/14 금
I/Adreno-EGL( 7357): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7357): Remote Branch: 
I/Adreno-EGL( 7357): Local Patches: 
I/Adreno-EGL( 7357): Reconstruct Branch: 
,I/NSApplication( 7357): Starting up...
,I/ActivityManager( 1038): Killing 6686:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6686/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2322): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2322): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7193): onReceive
,D/AppUp4:CustFacade( 7193): Context : android.app.ReceiverRestrictedContext@130443f6
D/AppUp4:CustFacade( 7193): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7193): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7193): begin check event
I/AppUp4:CustModeStarterReceiver( 7193): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3351): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3351): DownloadService onCreate
I/DownloadManager( 3351): in removeSpuriousFiles
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@3549741d on behalf of 3351
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4203): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3351): in trimDatabase
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 4203): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@3d157692 on behalf of 3351
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4203): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3351): DownloadService onStartCommand
V/DownloadManager( 3351): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4203): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4203): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/LgeMiscReceiver( 3305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3305): networkInfo.isConnected() = false
I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6942): 
W/Kids    ( 2322): [AccountUtils] Account not ready
W/Kids    ( 2322): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2322): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2322): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@3f8e3519 on behalf of 3351
,I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3351): processing inserted download 1
V/DownloadManager( 3351): processing inserted download 4
V/DownloadManager( 3351): processing inserted download 7
V/DownloadManager( 3351): processing inserted download 8
V/DownloadManager( 3351): processing inserted download 9
V/DownloadManager( 3351): processing inserted download 10
V/DownloadManager( 3351): processing inserted download 16
V/DownloadManager( 3351): processing inserted download 17
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3351): processing inserted download 18
V/DownloadManager( 3351): processing inserted download 21
V/DownloadManager( 3351): processing inserted download 22
,W/ResourcesManager( 1402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:1
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNLService( 1402): onNotificationPosted
V/DownloadManager( 3351): DownloadService onDestroy
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f29f264
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:1
W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{e1069de V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2322): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7193): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7193): onReceive
V/FormManager( 7255): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7255): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustFacade( 7193): Context : android.app.ReceiverRestrictedContext@130443f6
D/AppUp4:CustFacade( 7193): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7193): isPhone : true
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
D/AppUp4:CustModeStarterReceiver( 7193): begin check event
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
I/AppUp4:CustModeStarterReceiver( 7193): Event For GoodConnectivity, noConnectivity : false, but skip! 
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4203): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4203): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/libc-netbsd(  322): res_queryN name = mtalk.google.com succeed
,V/DownloadManager( 3351): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4203): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4203): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6942): 
V/DownloadManager( 3351): DownloadService onCreate
I/DownloadManager( 3351): in removeSpuriousFiles
I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6942): 
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@3cf2e7bf on behalf of 3351
,I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3351): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ContextImpl( 4203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3351): in trimDatabase
V/DownloadManager( 3351): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@32c30e8c on behalf of 3351
W/Kids    ( 2322): [AccountUtils] Account not ready
W/Kids    ( 2322): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2322): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2322): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|,1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
I/LgeMiscReceiver( 3305): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3305): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3305): networkInfo.isConnected() = true
D/PhoneState( 3305): setPdpRejectCasuse : false
E/LGDMClient( 4203): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3351): DownloadService onStartCommand
V/DownloadManager( 3351): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4203): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3351): created cursor android.database.sqlite.SQLiteCursor@23f840db on behalf of 3351
D/LGDMClient( 4203): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3351): processing inserted download 1
V/DownloadManager( 3351): processing inserted download 4
V/DownloadManager( 3351): processing inserted download 7
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{e1069de V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3351): processing inserted download 8
V/DownloadManager( 3351): processing inserted download 9
V/DownloadManager( 3351): processing inserted download 10
V/DownloadManager( 3351): processing inserted download 16
V/DownloadManager( 3351): processing inserted download 17
V/DownloadManager( 3351): processing inserted download 18
V/DownloadManager( 3351): processing inserted download 21
V/DownloadManager( 3351): processing inserted download 22
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:2
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f29f264
D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:32:2
V/DownloadManager( 3351): DownloadService onDestroy
,D/ChimeraCfgMgr( 2322): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7255): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7255): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2322): [AccountUtils] Account not ready
W/Kids    ( 2322): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2322): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2322): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2322): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2322): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2322): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6942): 
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=416820938, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/QRemote ( 7084): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7084): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4691
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{e1069de V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=416820938 [*alarm*], flags=0x0
,I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6942): 
,I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6942): 
,I/jxcore-log( 6942): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6942): 
D/GCM     ( 2117): Connected
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = www.google.com, class = 1, type = 1
D/GCM     ( 2117): Message class com.google.f.a.a.p
D/libc-netbsd(  322): res_queryN name = www.google.com succeed
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  322): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 6603): Internal timer expired: 4
D/UEI.SmartControl( 6603): unbind internal service
,D/serial_port( 6603): close(fd = 24)
,I/UEI.SmartControl( 6603): Serial port is closed.
I/GAV4    ( 7357): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6942): Test app app.js loaded
I/jxcore-log( 6942): 
,I/chromium( 6942): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6942): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6942): BLE advertisement is supported
I/jxcore-log( 6942): 
I/jxcore-log( 6942): --= Surplus to requirements =--
I/jxcore-log( 6942): 
I/jxcore-log( 6942): ****TEST TOOK:  ms ****
I/jxcore-log( 6942): 
I/jxcore-log( 6942): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6942): 
,D/AndroidRuntime( 7496): 
D/AndroidRuntime( 7496): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7496): CheckJNI is OFF
D/AndroidRuntime( 7496): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 6942:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1038): WIN DEATH: Window{33d35c7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{33d35c7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1038): Skipping PackageSetting{227032cf com.example.hello/10319} due to missing metadata
,E/libprocessgroup( 1038): failed to kill 1 processes for processgroup 6942
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3dcd9da1 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{294bd200 6942:com.test.thalitest/u0a311}, curProc for 6942: null
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3dcd9da1 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{3dcd9da1 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2073): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{1a4b82c6 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2073): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{1f233287 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2073): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
,E/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] [+] updateMediaPlayerInfo
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
,D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3673): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/art     ( 4408): Explicit concurrent mark sweep GC freed 15876(890KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 487us total 80.701ms
,W/System.err( 4363): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4363): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4363): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4363): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4363): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4363): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4363): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4363): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4363): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4363): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
,D/PostponalbeReceiver( 6443): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7529 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActionManagerService( 1910): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3673): handleMessage: what(1000) actionID(0x1000003)
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[LGHome]LGActivityUtil( 2073): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2073): [Launcher.java:1056:onResume()]onResume end
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 14.474ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 11.998ms
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5c2fbb8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2073): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 235us total 11.762ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 2073): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1910): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3673): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3673): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2073): , create_time: 1430558575574
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2073): , create_time: 1430558575600
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2073): , create_time: 1453982950152
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
,I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
,D/AppUp4:PreloadHelper( 7193): added Exclude : com.test.thalitest
I/art     ( 1038): Explicit concurrent mark sweep GC freed 39018(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.610ms total 250.985ms
I/art     ( 1038): WaitForGcToComplete blocked for 248.083ms for cause Explicit
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7548 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/LockScreenSettings( 7529): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3752): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1038): Handling package changes for user 0
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
I/ActivityManager( 1038): Killing 6802:com.lge.clock/u0a10 (adj 15): empty #17
W/ResourcesManager( 7548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7548): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7548): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7548): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7548): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/KeyguardModel( 1459): handleShortcutListChanged...
,W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_6802/cgroup.procs: No such file or directory
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
I/[LGHome]EVENT( 2073): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1459): createShortcutInfo...
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{10b0d7c6 u0 com.lge.launcher2/.Launcher t3} time:270090
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/SystemConfig( 7548): BUILD Country: EU
I/SystemConfig( 7548): BUILD Operator: OPEN
D/KeyguardModel( 1459): handleShortcutListChanged...
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2073): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2600): onStartCommand(). Type : 8
D/[Concierge]Service( 2600): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2600): Update widget ID : 11
D/[Concierge]WidgetView( 2073): change position of spinner
I/art     ( 1038): Explicit concurrent mark sweep GC freed 7592(407KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.035ms total 233.466ms
D/[Concierge]Service( 2600): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2073): initWebView(). Time : 1454056331040
I/ActivityManager( 1038): Killing 6716:com.google.android.apps.books/u0a54 (adj 15): empty #17
,D/AndroidRuntime( 7496): Shutting down VM
,W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WebView( 2073): Return exist ConciergeWebView. Reuse : 427757302
W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6716/cgroup.procs: No such file or directory
,D/[Concierge]WidgetView( 2073): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2073): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3e3c2054
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7548): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7548): existFile = false
I/PackageChangeReceiver( 7222): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/SystemConfig( 7548): canReadFile = false
I/SystemConfig( 7548): systemFeature RCS result false
D/SystemConfig( 7548): refreshRcsSupport() :false
D/VoicemailCleanupService( 2175): Cleaning up data for package: com.test.thalitest
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2073): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2073): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7570 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/[Concierge]WidgetView( 2073): Widget kill message received. Destory myself. My : 1454056087508, New one : 1454056331040
D/[Concierge]WidgetView( 2073): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2073): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7570): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7570): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7570): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7570): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2073): Timeline: Activity_idle id: android.os.BinderProxy@4716cb time:270478
,I/AppConfig( 7570): Total System Memory = 2995761152
,D/SystemHelper( 7570): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7570): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,I/ActivityManager( 1038): Killing 6136:com.android.vending/u0a44 (adj 15): empty #17
I/chromium( 2073): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2073): onReloaded()
,I/GBoardWebViewClient( 2073): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2030): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6136/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2030): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3673): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6443): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.

```
