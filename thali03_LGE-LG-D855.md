#### Test 54312298af2c956_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 278279272218; DSPS: 9259549; Offset : -4312735704
,D/AndroidRuntime( 7101): 
D/AndroidRuntime( 7101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7101): CheckJNI is OFF
D/AndroidRuntime( 7101): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1957): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{637b844 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{637b844 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7121 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7101): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1862): Display #0 changed.
D/SplitWindowPolicy( 1957): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1957): topRunningActivity=ActivityInfo{3ef7cb49 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1957): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1957): topRunningActivity=ActivityInfo{12e7fc4e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7121): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7121): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7121): Loading: webviewchromium
I/LibraryLoader( 7121): Time to load native libraries: 3 ms (timestamps 4102-4105)
I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7121): Binding Chromium to main looper Looper (main, tid 1) {39053d39}
I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
,I/chromium( 7121): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7121): Initializing chromium process, renderers=0
W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb1427c40, uid 10311
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@246072ae:true
W/chromium( 7121): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7121): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7121): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7121): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7121): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7121): Build Date: 12/12/14 금
I/Adreno-EGL( 7121): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7121): Remote Branch: 
I/Adreno-EGL( 7121): Local Patches: 
I/Adreno-EGL( 7121): Reconstruct Branch: 
,W/chromium( 7121): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7121): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7121): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7121): CordovaWebView is running on device made by: LGE
,W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7121): Render dirty regions requested: true
,I/OpenGLRenderer( 7121): Initialized EGL, version 1.4
D/OpenGLRenderer( 7121): Enabling debug mode 0
,W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{28765d2d u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 7121): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{e8d34f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7121): LgDataFeature() Constructor: none
D/LgDataFeature( 7121): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@10021401,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +668ms (total +762ms)
I/Timeline( 7121): Timeline: Activity_idle id: android.os.BinderProxy@2d52e6a9 time:284593
,I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{28765d2d u0 com.test.thalitest/.MainActivity t4} time:284594
I/chromium( 7121): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7121): 
,D/JsMessageQueue( 7121): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7121): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7121): 
,D/jxcore_app_log( 7121): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435073280
D/JX-Cordova( 7121): jxcore cordova android initializing
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7121): Initializing JXcore engine
W/jxcore-log( 7121): JXcore engine is ready
,W/jxcore-log( 7121): Starting JXcore engine
W/.test.thalitest( 7121): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9810]" dev="sockfs" ino=9810 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7121): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 7121): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10368]" dev="sockfs" ino=10368 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7121): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7121): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32493]" dev="sockfs" ino=32493 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7121): Background sticky concurrent mark sweep GC freed 124122(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.652ms total 127.811ms
,W/jxcore-log( 7121): Platform android
W/jxcore-log( 7121): 
W/jxcore-log( 7121): Process ARCH arm
W/jxcore-log( 7121): 
,I/jxcore-log( 7121): JXcore Cordova bridge is ready!
I/jxcore-log( 7121): 
W/jxcore-log( 7121): JXcore engine is started
,I/jxcore-log( 7121): Toggling radios to true
I/jxcore-log( 7121): 
,D/BluetoothAdapter( 7121): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7121, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7121, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7121, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [287,913,903 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7121, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7121): Radios toggled
I/jxcore-log( 7121): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7121): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Perf Test app loaded loaded
I/jxcore-log( 7121): 
I/jxcore-log( 7121): check test folder
I/jxcore-log( 7121): 
I/jxcore-log( 7121): found test : ./testFindPeers.js
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): found test : ./testSendData.js
I/jxcore-log( 7121): 
,I/wpa_supplicant( 2736): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering( 1037): InitialState.processMessage what=4
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 7121): found test : ./testSendData2.js
I/jxcore-log( 7121): 
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/DhcpStateMachine( 1037): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Clearing all IP addresses on wlan0
V/NativeCrypto( 2124): Read error: ssl=0xaf498a00: I/O error during system call, Connection timed out
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [288,078,660 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
,I/wpa_supplicant( 2736): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=288080
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=288080
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
V/WfdStateTracker( 1957): handleWifiStateChangedEvent: 0
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
I/chromium( 7121): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7121): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 2124): Explicit concurrent mark sweep GC freed 35370(2MB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 29.299ms total 119.361ms
V/NativeCrypto( 2124): SSL shutdown failed: ssl=0xaf498a00: I/O error during system call, Broken pipe
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  311): Clearing all IP addresses on wlan0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1037): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=288134  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=288135  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=288143  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=288146  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7199): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7199): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/ResourcesManager( 7199): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
W/ResourcesManager( 7199): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
W/ResourcesManager( 7199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable:, true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1862): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-123ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7199): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7199): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7199): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7199): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6103:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6103/cgroup.procs: No such file or directory
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 50331(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.477ms total 135.696ms
,I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7199): LgDataFeature() Constructor: none
,D/LgDataFeature( 7199): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7261 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6126:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6126/cgroup.procs: No such file or directory
,W/ResourcesManager( 7261): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7261): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7261): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7261): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7261): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7261): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7261): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7261): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7261): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7261): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
,D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7261): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7261): LgDataFeature() Constructor: none
D/LgDataFeature( 7261): LgDataFeature() Constructor Done, null
,V/SoundPool( 7261): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7261): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7261): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7261): doLoad: loading sample sampleID=1
I/QRemote ( 7261): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7261): Start decode
V/MediaPlayer[Native]( 7261): decode(31, 10857164, 17813)
,V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
D/UEI.SmartControl( 6802): QS Service created
,V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1163a00, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/QRemote ( 7261): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7261): Create singleton instance
,I/UEI.SmartControl( 6802): Service initServices...
,D/UEI.SmartControl( 6802): QS start get config
V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
,V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14347e0 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMX,Codec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb1163a00, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1163a00, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976544
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1a0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1163a00, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf406000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf407000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf408000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf409000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40a000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40b000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40c000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40d000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40e000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf40f000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf410000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf411000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf412000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf413000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf414000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf415000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf416000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf417000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf418000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf419000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41a000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41b000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41c000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41d000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41e000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf41f000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf420000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf421000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf422000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf423000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf424000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf425000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf426000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf427000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf428000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
,V/AudioCache(  316): memcpy(0xaf429000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42a000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42b000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42c000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42d000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42e000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf42f000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf430000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf431000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf432000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf433000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf434000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf435000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf436000, 0xb1250000, 4096)
V/AudioCache(  316): write(0xb1250000, 4096)
V/AudioCache(  316): memcpy(0xaf437000, 0xb1250000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb1250000, 280)
V/AudioCache(  316): memcpy(0xaf438000, 0xb1250000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1163a00, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb1163a00, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1163a00, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1a0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7261): close(31)
V/SoundPool( 7261): pointer = 0x9ffe0000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8846
,I/UEI.SmartControl( 6802): Supports setup maps: true
,D/UEI.SmartControl( 6802): QS start statue = true Error code = 0
I/UEI.SmartControl( 6802): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6802): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6802): ### init IR Blaster...
D/serial_port( 6802): Configuring serial port
E/UEI.SmartControl( 6802): UEIBLaster setting for 616
I/UEI.SmartControl( 6802): Setting serial record hearder size = 2
,I/UEI.SmartControl( 6802): configuring settings for MAXQ616
I/UEI.SmartControl( 6802): Get version...
D/UEI.SmartControl( 6802): serial port data available: 21
,D/UEI.SmartControl( 6802): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6802): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6802): QS saving settings...
,D/UEI.SmartControl( 6802): IR Blaster version: 25672567
D/UEI.SmartControl( 6802): serial port data available: 4
,I/UEI.SmartControl( 6802): Device manager: loading config....,
,D/UEI.SmartControl( 6802): ----------- loading internal config...
W/ContextImpl( 6802): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6802): Services init done
D/UEI.SmartControl( 6802): QS Service init finished
D/UEI.SmartControl( 6802): QS Service version name: 2.1.91
D/UEI.SmartControl( 6802): QS Service version code: 201091
D/UEI.SmartControl( 6802): Service requested: Control
E/UEI.SmartControl( 6802): Loading SETTINGS...
,D/UEI.SmartControl( 6802): Request IControl service: devices are loaded...
I/QRemote ( 7261): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6802): Internal service binding...
I/UEI.SmartControl( 6802): ------ IControl API: 11
D/UEI.SmartControl( 6802): File observer start...
E/UEI.SmartControl( 6802): IR Port is disabled: false
D/UEI.SmartControl( 6802): Starting file observer...
I/UEI.SmartControl( 6802): Registering callback...
,D/UEI.SmartControl( 6802): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6802): ------ IControl API: 19
I/UEI.SmartControl( 6802): Registering Services Ready callback...
I/UEI.SmartControl( 6802): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6802): -----service ready thread exits
I/QRemote ( 7261): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7261): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7261): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7261): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7261): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6802): ------ IControl API: 8
D/QRemote ( 7261): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7261): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7261): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7261): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 7261): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7261): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7261): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7261): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7261): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450836718103]
,D/QRemote ( 7261): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6697:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7261): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6697/cgroup.procs: No such file or directory
,V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7261): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2736): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=290218  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=290239  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
I/wpa_supplicant( 2736): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2736): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2736): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=290336  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=290341  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=290345
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=290345
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=290346
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=290346
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=290347
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=290347  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=290385  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=290387  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=290389  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=290391
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=290392
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7199): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7199): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7199): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7199): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7199): [AUTORUN] setTetherStatus() : status=false
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=290442  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=290443  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=290443  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1037): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=290447  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=290448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=290448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36ce2678 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36ce2678 target=com.android.internal.util.StateMachine$SmHandler }
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
,D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1957): handleWifiStateChangedEvent: 1,
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=10485,76Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1862): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
W/dsqn    ( 7342): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7342): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/DSQN    ( 7342): DSQN ssw
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7261): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7261): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7261): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 7199): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 02:11:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450836719024], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450836719005]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7261): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QRemote ( 7261): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyNetworkFactory-1( 1862): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7348): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7348): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7348): version 5.5.6 starting
E/dhcpcd  ( 7348): get_duid: m
D/dhcpcd  ( 7348): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7348): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7348): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7348): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7348): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7348): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7348): wlan0: sending REQUEST (xid 0xf2fce39a), next in 3.56 seconds
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5462): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5462): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7366 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7366): onCreate
,W/AppUp4:DB( 7366):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7366):  setFingerPrint start
I/AppUp4:DB( 7366):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7366):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7366):  SDK version = 21
,I/AppUp4:DB( 7366):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7366): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7366): onReceive
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524295
D/LgDataFeature( 7366): LgDataFeature() Constructor: none
,D/LgDataFeature( 7366): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7366): Context : android.app.ReceiverRestrictedContext@de87cdf
D/AppUp4:CustFacade( 7366): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7366): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7366): begin check event
I/AppUp4:CustModeStarterReceiver( 7366): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7366): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7366): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7366): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7366): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6729:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6729/cgroup.procs: No such file or directory
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3390): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3390): DownloadService onCreate
D/LGDMClient( 4330): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4330): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3390): in removeSpuriousFiles
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@e3baf53 on behalf of 3390
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3390): in trimDatabase
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@2c072090 on behalf of 3390
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7417 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3390): DownloadService onStartCommand
V/DownloadManager( 3390): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 21.223ms
,V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@2a47edaf on behalf of 3390
E/LGDMClient( 4330): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/jxcore-log( 7121): Connected to the server!
I/jxcore-log( 7121): 
D/LGDMClient( 4330): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4330): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3390): processing inserted download 1
V/DownloadManager( 3390): processing inserted download 4
V/DownloadManager( 3390): processing inserted download 7
V/DownloadManager( 3390): processing inserted download 8
V/DownloadManager( 3390): processing inserted download 9
V/DownloadManager( 3390): processing inserted download 10
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.427ms
V/DownloadManager( 3390): processing inserted download 16
V/DownloadManager( 3390): processing inserted download 17
V/DownloadManager( 3390): processing inserted download 18
V/DownloadManager( 3390): processing inserted download 21
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 14.818ms
I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
V/DownloadManager( 3390): DownloadService onDestroy
W/ResourcesManager( 7417): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
W/ResourcesManager( 7417): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7417): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
I/LGEmail ( 7417): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7417): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7417): No package identifier when getting value for resource number 0x00000000
I/dhcpcd  ( 7348): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7348): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7348): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7348): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7348): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7348): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7348): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7348): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7348): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/LgDataFeature( 7417): LgDataFeature() Constructor: none
D/LgDataFeature( 7417): LgDataFeature() Constructor Done, null
D/eas_req ( 7417): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7462 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 7417): JNI_OnLoad()
I/HubEmail( 7417): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7417): registerNatives()
I/HubEmail( 7417): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7417): registerNativeMethods()
I/HubEmail( 7417): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7417): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6569:com.android.defcontainer/u0a4 (adj 15): empty #17
W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6569/cgroup.procs: No such file or directory
W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3357): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3357): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3357): networkInfo.isConnected() = false
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7486 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
V/FormManager( 7462): There are no updated forms. The schedule will be deleted.
V/FormManager( 7462): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7507 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6750:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6750/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6777:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7524 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6855:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6777/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6855/cgroup.procs: No such file or directory
I/art     ( 7524): Almond Protected OAT
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7121): BLE supported!!
I/jxcore-log( 7121): 
,D/WeatherApplication( 7524): removeAccount
,D/WeatherApplication( 7524): Account.length = 0
E/WeatherApplication( 7524): OPERATOR:OPEN
,D/WeatherAncestor( 7524): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:1
,D/Weather.Utils( 7524): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7524): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7524): 2 : This is isUpdating : false
D/WeatherAncestor( 7524): connectivity changed - connection : true
,D/WeatherService( 7524): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7524): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7524): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7524): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7524): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7524): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:1
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7542 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6828:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6828/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7542): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5462): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7542): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7542): Loading: webviewchromium
I/LibraryLoader( 7542): Time to load native libraries: 3 ms (timestamps 3618-3621)
I/LibraryLoader( 7542): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7542): Binding Chromium to main looper Looper (main, tid 1) {1e4b06}
,I/LibraryLoader( 7542): Expected native library version number "",actual native library version number ""
,I/chromium( 7542): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7542): Initializing chromium process, renderers=0
W/art     ( 7542): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7542): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7542): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7542): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  316): registerClient() client 0xb1427da0, uid 10093
W/AudioManagerAndroid( 7542): Requires BLUETOOTH permission
I/Adreno-EGL( 7542): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7542): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7542): Build Date: 12/12/14 금
I/Adreno-EGL( 7542): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7542): Remote Branch: 
I/Adreno-EGL( 7542): Local Patches: 
I/Adreno-EGL( 7542): Reconstruct Branch: 
,I/NSApplication( 7542): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7597 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6878:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6878/cgroup.procs: No such file or directory
,W/ResourcesManager( 7597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSActivity( 2124): [ac] getting account id
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2124): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7366): onReceive
,D/AppUp4:CustFacade( 7366): Context : android.app.ReceiverRestrictedContext@de87cdf
D/AppUp4:CustFacade( 7366): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7366): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7366): begin check event
I/AppUp4:CustModeStarterReceiver( 7366): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3390): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3390): DownloadService onCreate
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4330): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4330): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3390): in removeSpuriousFiles
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3390): DownloadService onStartCommand
V/DownloadManager( 3390): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@182fb5cb on behalf of 3390
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@3bb671a8 on behalf of 3390
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
E/LGDMClient( 4330): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,D/LGDMClient( 4330): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4330): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3390): in trimDatabase
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3390): processing inserted download 1
,V/DownloadManager( 3390): processing inserted download 4
V/DownloadManager( 3390): processing inserted download 7
V/DownloadManager( 3390): processing inserted download 8
V/DownloadManager( 3390): processing inserted download 9
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@133fc4c1 on behalf of 3390
V/DownloadManager( 3390): processing inserted download 10
V/DownloadManager( 3390): processing inserted download 16
W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3357): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3357): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3357): networkInfo.isConnected() = false
D/WeatherAncestor( 7524): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:2
,V/DownloadManager( 3390): processing inserted download 17
W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3390): processing inserted download 18
,V/DownloadManager( 3390): processing inserted download 21
D/Weather.Utils( 7524): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7524): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7524): 2 : This is isUpdating : false
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
D/WeatherAncestor( 7524): connectivity changed - connection : true
D/WeatherService( 7524): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@267373f5
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/ForecastDataCache( 7524): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7524): 2 : currentPackageVersion: 4.40.4
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 7524): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7524): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7524): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:2
W/Kids    ( 2353): [AccountUtils] Account not ready
W/Kids    ( 2353): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2353): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2353): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3390): DownloadService onDestroy
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7462): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7462): Alarm would be updated, because LastCheckTime has been updated.
,D/UEI.SmartControl( 6802): Internal timer expired: 4
D/UEI.SmartControl( 6802): unbind internal service
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 56682(2MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 1.929ms total 141.289ms
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7366): [onReceive] request level :IDLE....
,D/libc-netbsd(  311): res_queryN name = www.google.com succeed
I/AppUp4:CustModeStarterReceiver( 7366): onReceive
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/AppUp4:CustFacade( 7366): Context : android.app.ReceiverRestrictedContext@de87cdf
D/AppUp4:CustFacade( 7366): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7366): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7366): begin check event
I/AppUp4:CustModeStarterReceiver( 7366): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3390): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4330): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4330): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3390): DownloadService onCreate
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3390): in removeSpuriousFiles
I/LGDMClient( 4330): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@1981e3a7 on behalf of 3390
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3390): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3390): in trimDatabase
V/DownloadManager( 3390): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@29d50054 on behalf of 3390
W/ContextImpl( 4330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4330): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4330): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4330): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/serial_port( 6802): close(fd = 24)
I/UEI.SmartControl( 6802): Serial port is closed.
V/DownloadManager( 3390): DownloadService onStartCommand
I/LgeMiscReceiver( 3357): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3357): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3357): networkInfo.isConnected() = true
D/PhoneState( 3357): setPdpRejectCasuse : false
V/DownloadManager( 3390): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
V/DownloadManager( 3390): created cursor android.database.sqlite.SQLiteCursor@fdf1343 on behalf of 3390
W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3390): processing inserted download 1
V/DownloadManager( 3390): processing inserted download 4
V/DownloadManager( 3390): processing inserted download 7
V/DownloadManager( 3390): processing inserted download 8
V/DownloadManager( 3390): processing inserted download 9
,V/DownloadManager( 3390): processing inserted download 10
V/DownloadManager( 3390): processing inserted download 16
V/DownloadManager( 3390): processing inserted download 17
V/DownloadManager( 3390): processing inserted download 18
D/WeatherAncestor( 7524): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:3
V/DownloadManager( 3390): processing inserted download 21
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Weather.Utils( 7524): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7524): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7524): 2 : This is isUpdating : false
D/WeatherAncestor( 7524): connectivity changed - connection : true
D/WeatherService( 7524): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@267373f5
,D/ForecastDataCache( 7524): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7524): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7524): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7524): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7524): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:12:3
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3390): DownloadService onDestroy
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
W/Kids    ( 2353): [AccountUtils] Account not ready
W/Kids    ( 2353): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2353): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2353): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7462): There are no updated forms. The schedule will be deleted.
V/FormManager( 7462): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
W/Kids    ( 2353): [AccountUtils] Account not ready
W/Kids    ( 2353): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2353): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2353): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2353): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2353): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2353): 	at java.lang.Thread.run(Thread.java:818)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2ad5f7a7 type 2 when 271560 android} when 271560
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{20b98454 type 2 when 293459 com.google.android.gms} when 293459
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
D/[Concierge]Service( 2599): onStartCommand(). Type : 9
,V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8846
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2124): Connected
,D/GCM     ( 2124): Message class com.google.f.a.a.p
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 298281799993; DSPS: 9914992; Offset : -4312741071
,I/GAV4    ( 7542): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1037): Killing 6902:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6902/cgroup.procs: No such file or directory
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{24606743 type 2 when 303667 android} when 303667
,I/BooksSync( 6955): Starting books sync
,D/BooksSync( 6955): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7750039692430127260&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7750039692430127260&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446),
E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7750039692430127260&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
E/BooksSync( 6955): Soft error: 
E/BooksSync( 6955): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7750039692430127260&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6955): Headers:
E/BooksSync( 6955): accept-encoding: [gzip]
E/BooksSync( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6955): gdata-version: 2
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6955): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6955): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6955): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6955): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6955): {
E/BooksSync( 6955):  "error": {
E/BooksSync( 6955):   "errors": [
E/BooksSync( 6955):    {
E/BooksSync( 6955):     "domain": "global",
E/BooksSync( 6955):     "reason": "required",
E/BooksSync( 6955):     "message": "Login Required",
E/BooksSync( 6955):     "locationType": "header",
E/BooksSync( 6955):     "location": "Authorization"
E/BooksSync( 6955):    }
E/BooksSync( 6955):   ],
E/BooksSync( 6955):   "code": 401,
E/BooksSync( 6955):   "message": "Login Required"
E/BooksSync( 6955):  }
E/BooksSync( 6955): }
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6955): 	... 8 more
,E/BooksSync( 6955): Sync error
E/BooksSync( 6955): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7750039692430127260&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6955): Headers:
E/BooksSync( 6955): accept-encoding: [gzip]
E/BooksSync( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6955): gdata-version: 2
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6955): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6955): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6955): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6955): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6955): {
E/BooksSync( 6955):  "error": {
E/BooksSync( 6955):   "errors": [
E/BooksSync( 6955):    {
E/BooksSync( 6955):     "domain": "global",
E/BooksSync( 6955):     "reason": "required",
E/BooksSync( 6955):     "message": "Login Required",
E/BooksSync( 6955):     "locationType": "header",
E/BooksSync( 6955):     "location": "Authorization"
E/BooksSync( 6955):    }
E/BooksSync( 6955):   ],
E/BooksSync( 6955):   "code": 401,
E/BooksSync( 6955):   "message": "Login Required"
E/BooksSync( 6955):  }
E/BooksSync( 6955): }
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6955): 	... 8 more
I/BooksSync( 6955): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 303667, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 318283850819; DSPS: 10570419; Offset : -4312734896
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{314bce95 type 2 when 333705 android} when 333705
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 338286309822; DSPS: 11225860; Offset : -4312747713
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=528938887, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/[Concierge]Service( 2599): onStartCommand(). Type : 9
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=528938887 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 358288371897; DSPS: 11881287; Offset : -4312730394
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/LEDHandler( 1957): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1957): Battery Level Remaining: 100%
D/LEDHandler( 1957): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1444): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1444): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3823): Disconnected process message: 10, size: 0
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4330): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6216): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6216): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6216): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6216): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6216): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6216): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6216): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6216): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 378291112463; DSPS: 12536737; Offset : -4312736177
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 398293675424; DSPS: 13192181; Offset : -4312737003
,I/jxcore-log( 7121): --- start :testFindPeers.js---
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): testFindPeers created [object Object]
I/jxcore-log( 7121): 
I/jxcore-log( 7121): serverPort is 8876
I/jxcore-log( 7121): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3911
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7121): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3823): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): start: OK
I/io.jxcore.node.ConnectionHelper( 7121): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3911
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7121): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7121): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a45933c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a45933c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
,D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433393131222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433393131222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7121): start: OK
I/jxcore-log( 7121): StartBroadcasting started ok
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7121): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 7121): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,I/jxcore-log( 7121): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6430","peerAvailable":true}]
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): weAreDoneNow
I/jxcore-log( 7121): 
I/jxcore-log( 7121): done, now sending data to server
I/jxcore-log( 7121): 
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-28ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-29ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-29ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-33ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-33ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-33ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-37ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-37ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-37ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 418297360051; DSPS: 13847662; Offset : -4312744873
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 68000101000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] is available
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 438299204627; DSPS: 14503082; Offset : -4312731430
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2736): P2P-FIND-STOPPED 
D/WfdsMonitor( 1957): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true,
,D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 458301363422; DSPS: 15158513; Offset : -4312739306
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=77 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=85 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=86 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=90 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=91 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=92 dispatchEvent: P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=93 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1957): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] is available
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000103000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] is available
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=97 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
,I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=528938887, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7741 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2599): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7741): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7741): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@6ed2100
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=528938887 [*alarm*], flags=0x0
I/ActivityManager( 1037): Killing 6216:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6216/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=99 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=101 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=102 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0,
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=104 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 478303292424; DSPS: 15813936; Offset : -4312733041
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430],
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again,
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=110 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=111 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=114 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=116 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-26ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-26ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-26ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=120 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=122 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=123 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=124 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=127 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=128 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 498305261375; DSPS: 16469361; Offset : -4312747524,
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=129 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=130 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=131 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=132 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=134 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledSt,ate{ when=-1ms what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=51 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=51 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=135 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=136 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 1,2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=139 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 68000106000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=140 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] is available
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=141 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 518307753971; DSPS: 17124802; Offset : -4312726905
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=142 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001090a436f72646f7661703270c00c000c01
I/jxcore-log( 7121): teardown
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): testFindPeers stopped
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2736): P2P-FIND-STOPPED 
D/WfdsMonitor( 1957): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-FIND-STOPPED 
,D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7121): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setState: NOT_STARTED
I/jxcore-log( 7121): StopBroadcasting went ok
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7121): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7121): --- start :testSendData.js---
I/jxcore-log( 7121): 
I/jxcore-log( 7121): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): check server
I/jxcore-log( 7121): 
I/jxcore-log( 7121): serverPort is 58226
I/jxcore-log( 7121): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3911
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7121): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): start: OK
I/io.jxcore.node.ConnectionHelper( 7121): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3911
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7121): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7121): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a45933c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a45933c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433393131222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505433393131222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=144 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7121): start: OK
I/jxcore-log( 7121): StartBroadcasting started ok
I/jxcore-log( 7121): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Waiting for incoming connections...
,I/jxcore-log( 7121): null
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:15:57.135Z SendDataTCPServer.js: TCP/IP server is bound to port: 58226
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2736): P2P-FIND-STOPPED 
D/WfdsMonitor( 1957): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7121): onDiscoveryManagerStateChanged: RUNNING
,I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=146 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=147 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 538310391516; DSPS: 17780249; Offset : -4312744441
,I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.Disco,veryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=150 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000107000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000107000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000107000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=153 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=154 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=155 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=157 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers,: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=159 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=15 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=15 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=161 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010b0a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=162 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=164 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 68000108000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86,
,W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=165 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] is available
,I/jxcore-log( 7121): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT4270","peerAvailable":true}]
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Found peer : samsung-SM-A300FU_PT4270, Available: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): startWithNextDevice
I/jxcore-log( 7121): 
I/jxcore-log( 7121): device[1]: 08:EC:A9:50:75:41
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:20.135Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:20.135Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:20.135Z SendDataConnector.js: do connect now
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7121): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 821)
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3823): [BTUI] connectSocket FD=85 mFd=84
W/bt-btm  ( 3823): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3823): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3823): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-btm  ( 3823): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=167 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01
W/bt-btm  ( 3823): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3823): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3823): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3823): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
W/bt-btif ( 3823): info:x10
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3823): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3823): aclStateChangeCallback: Device is NULL
W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
D/LGBluetoothServiceUtil( 3823): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3823): process_service_search_attr_rsp
W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0040
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee11d98:true
,D/LGBluetoothFeatureConfig( 7199): isPrivacyLogsEnabled : true
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 21
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3823): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3823): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3823): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3823): Entering PendingCommandState State
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7803 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothRemoteDevices( 3823): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3823): Failed to remove device: 08:EC:A9:50:75:41
I/BluetoothBondStateMachine( 3823): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
W/bt-btm  ( 3823): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,I/BluetoothBondStateMachine( 3823): StableState(): Entering Off State
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@342ea9d6:true
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3823): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3823): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 821)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesWritten: 77 bytes successfully written (thread ID: 822)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Outgoing connection initialized (*handshake* thread ID: 822)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Exiting thread (thread ID: 821)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Entering thread (ID: 822)
E/ActivityThread( 7803): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7803): No ProfileInfo entries
I/LG Account v2.2( 7803): isEnabled: false
I/Feature ( 7803): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7803): [Lifetracker]Country: EU
I/Feature ( 7803): [Lifetracker]Operator: OPEN
I/Feature ( 7803): [Lifetracker]Ranking support: false
I/Feature ( 7803): [Lifetracker]Comfort support: false
I/Feature ( 7803): [Lifetracker]Accessory: true
I/Feature ( 7803): [Lifetracker]Health device: true
I/Feature ( 7803): [Lifetracker]Extra Pedometer: false
I/Feature ( 7803): [Lifetracker]Blood glucose device: false
I/Feature ( 7803): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 7237:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7237/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesRead: Read 83 bytes successfully (thread ID: 822)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Exiting thread (ID: 822)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7121): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7121): Entering thread (ID: 823)
D/io.jxcore.node.OutgoingSocketThread( 7121): Server socket local port: 59642
I/io.jxcore.node.OutgoingSocketThread( 7121): Now accepting connections...
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010d0a436f72646f7661703270c00c000c01],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=168 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010d0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01
I/io.jxcore.node.ConnectionHelper( 7121): onListeningForIncomingConnections: Outgoing connection is using port 59642 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 7121): 2015-12-23T02:16:22.806Z SendDataConnector.js: CLIENT connected to 59642, error: null
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:22.807Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7121): 
,I/io.jxcore.node.OutgoingSocketThread( 7121): Incoming data from address: /127.0.0.1, port: 59642
D/io.jxcore.node.OutgoingSocketThread( 7121): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7121): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7121): Exiting thread (ID: 823)
,D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 825, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 824, name: Sender)
I/jxcore-log( 7121): 2015-12-23T02:16:22.843Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7121): 
D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,I/jxcore-log( 7121): 2015-12-23T02:16:23.544Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7121): 
,D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18320
,I/jxcore-log( 7121): 2015-12-23T02:16:23.589Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7121): 
D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10400
,I/jxcore-log( 7121): 2015-12-23T02:16:23.924Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:23.949Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7121): 
,D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3470
,I/jxcore-log( 7121): 2015-12-23T02:16:23.997Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:24.101Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:24.163Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:24.285Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:24.345Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:24.358Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:24.359Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): oneRoundDownNow
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:24.367Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:24.367Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7121): 
D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 7121): close
D/io.jxcore.node.OutgoingSocketThread( 7121): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 825
D/io.jxcore.node.OutgoingSocketThread( 7121): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 824
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 824, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7121): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 825, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 824, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 825, name: Receiver)
I/jxcore-log( 7121): 2015-12-23T02:16:24.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 7121): 
I/jxcore-log( 7121): ---- round done--------
I/jxcore-log( 7121): 
I/jxcore-log( 7121): startWithNextDevice
I/jxcore-log( 7121): 
W/bt-rfcomm( 3823): rfc_port_closed
W/bt-btif ( 3823): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0041
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 558312831092; DSPS: 18435689; Offset : -4312746193
,E/bt-btm  ( 3823): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -1
,I/BluetoothMapService( 3823): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3823): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3823): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3823): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3823): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3823): state: -2147483648
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL disconnected => AclLinkCount = 0
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32967b44:true
,I/BTConnectionReceiver( 4598): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4598): Bluetooth Device Name: A3-1
D/btif_config_util( 3823): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=170 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=171 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsun,g-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=172 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=173 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 7 1200010c0a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=174 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=175 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=176 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=177 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000106000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505431303033222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] is available
I/jxcore-log( 7121): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT1003","peerAvailable":true}]
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Found peer : samsung-SM-N910C_PT1003, Available: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): startWithNextDevice
I/jxcore-log( 7121): 
I/jxcore-log( 7121): device[2]: E0:DB:10:14:E2:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:30.554Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:30.554Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:30.554Z SendDataConnector.js: do connect now
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 7121): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 826)
W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: e0db1014e2c0  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3823): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btm  ( 3823): btm_acl_created hci_handle=4 link_role=0  transport=1
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3823): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
,W/bt-btm  ( 3823): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3823): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 3823): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
W/bt-btif ( 3823): info:x10
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3823): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3823): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3823): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3823): process_service_search_attr_rsp
W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0042
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: e0db1014e2c0  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 21
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL connected => AclLinkCount = 1
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3823): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3823): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3823): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3823): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothRemoteDevices( 3823): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3823): Failed to remove device: E0:DB:10:14:E2:C0
I/BluetoothBondStateMachine( 3823): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3823): StableState(): Entering Off State
,W/bt-btm  ( 3823): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0046,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0046,PSM: 3,peer MTU present: 0,peer MTU: 1691
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3823): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3823): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 826)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesWritten: 77 bytes successfully written (thread ID: 827)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Outgoing connection initialized (*handshake* thread ID: 827)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Exiting thread (thread ID: 826)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Entering thread (ID: 827)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesRead: Read 82 bytes successfully (thread ID: 827)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7121): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Exiting thread (ID: 827)
D/io.jxcore.node.OutgoingSocketThread( 7121): Entering thread (ID: 828)
D/io.jxcore.node.OutgoingSocketThread( 7121): Server socket local port: 49064
I/io.jxcore.node.OutgoingSocketThread( 7121): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7121): onListeningForIncomingConnections: Outgoing connection is using port 49064 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 7121): 2015-12-23T02:16:32.468Z SendDataConnector.js: CLIENT connected to 49064, error: null
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:32.469Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7121): 
,I/io.jxcore.node.OutgoingSocketThread( 7121): Incoming data from address: /127.0.0.1, port: 49064
D/io.jxcore.node.OutgoingSocketThread( 7121): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7121): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7121): Exiting thread (ID: 828)
,I/jxcore-log( 7121): 2015-12-23T02:16:32.497Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7121): 
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 830, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 829, name: Sender)
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=528938887, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3e39642d type 2 when 564413 android} when 564413
D/[Concierge]Service( 2599): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=528938887 [*alarm*], flags=0x0
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 63991(3MB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 2.577ms total 152.302ms
,I/BooksSync( 6955): Starting books sync
D/BooksSync( 6955): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=179 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 7121): 2015-12-23T02:16:33.306Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.374Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.386Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:33.390Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:33.434Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.472Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.568Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.586Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:16:33.645Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:33.649Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7121): 
I/jxcore-log( 7121): oneRoundDownNow
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:33.651Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:33.652Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7121): 
D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 7121): close
D/io.jxcore.node.OutgoingSocketThread( 7121): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 830
D/io.jxcore.node.OutgoingSocketThread( 7121): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 829
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 829, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7121): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7121): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 830, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 829, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 830, name: Receiver)
I/jxcore-log( 7121): 2015-12-23T02:16:33.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): ---- round done--------
I/jxcore-log( 7121): 
I/jxcore-log( 7121): startWithNextDevice
I/jxcore-log( 7121): 
W/bt-rfcomm( 3823): rfc_port_closed
W/bt-btif ( 3823): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0043
W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010e0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=180 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010e0a436f72646f7661703270c00c000c01
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4016805001024962803&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=182 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=183 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=184 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2m,s what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-25ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-25ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thal,iproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4016805001024962803&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
E/bt-btm  ( 3823): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1037): Connected BT device : -2
,I/BluetoothMapService( 3823): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3823): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3823): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3823): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3823): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3823): state: -2147483648
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4598): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4598): Bluetooth Device Name: Note4-1
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/btif_config_util( 3823): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/BooksAccountManager( 6955): Authentication error
E/BooksAccountManager( 6955): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6955): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6955): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6955): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6955): null auth token
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1981e3a7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6955): Error response from books API: {
W/ApiaryClient( 6955):  "error": {
W/ApiaryClient( 6955):   "errors": [
W/ApiaryClient( 6955):    {
W/ApiaryClient( 6955):     "domain": "global",
W/ApiaryClient( 6955):     "reason": "required",
W/ApiaryClient( 6955):     "message": "Login Required",
W/ApiaryClient( 6955):     "locationType": "header",
W/ApiaryClient( 6955):     "location": "Authorization"
W/ApiaryClient( 6955):    }
W/ApiaryClient( 6955):   ],
W/ApiaryClient( 6955):   "code": 401,
W/ApiaryClient( 6955):   "message": "Login Required"
W/ApiaryClient( 6955):  }
W/ApiaryClient( 6955): }
,W/ApiaryClient( 6955): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4016805001024962803&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6955): Headers:
W/ApiaryClient( 6955): accept-encoding: [gzip]
W/ApiaryClient( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6955): gdata-version: 2
,E/BooksSync( 6955): Soft error: 
E/BooksSync( 6955): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4016805001024962803&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6955): Headers:
E/BooksSync( 6955): accept-encoding: [gzip]
E/BooksSync( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6955): gdata-version: 2
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6955): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6955): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6955): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6955): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6955): {
E/BooksSync( 6955):  "error": {
E/BooksSync( 6955):   "errors": [
E/BooksSync( 6955):    {
E/BooksSync( 6955):     "domain": "global",
E/BooksSync( 6955):     "reason": "required",
E/BooksSync( 6955):     "message": "Login Required",
E/BooksSync( 6955):     "locationType": "header",
E/BooksSync( 6955):     "location": "Authorization"
E/BooksSync( 6955):    }
E/BooksSync( 6955):   ],
E/BooksSync( 6955):   "code": 401,
E/BooksSync( 6955):   "message": "Login Required"
E/BooksSync( 6955):  }
E/BooksSync( 6955): }
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6955): 	... 8 more
,E/BooksSync( 6955): Sync error
E/BooksSync( 6955): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6955): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4016805001024962803&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6955): Headers:
E/BooksSync( 6955): accept-encoding: [gzip]
E/BooksSync( 6955): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6955): gdata-version: 2
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6955): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6955): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6955): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6955): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6955): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6955): {
E/BooksSync( 6955):  "error": {
E/BooksSync( 6955):   "errors": [
E/BooksSync( 6955):    {
E/BooksSync( 6955):     "domain": "global",
E/BooksSync( 6955):     "reason": "required",
E/BooksSync( 6955):     "message": "Login Required",
E/BooksSync( 6955):     "locationType": "header",
E/BooksSync( 6955):     "location": "Authorization"
E/BooksSync( 6955):    }
E/BooksSync( 6955):   ],
E/BooksSync( 6955):   "code": 401,
E/BooksSync( 6955):   "message": "Login Required"
E/BooksSync( 6955):  }
E/BooksSync( 6955): }
E/BooksSync( 6955): 
E/BooksSync( 6955): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6955): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6955): 	... 8 more
I/BooksSync( 6955): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 564413, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=185 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=187 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001040a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=188 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001060a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001060a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=189 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=190 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010a000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010a000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=191 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010a000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505431373135222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 578316561188; DSPS: 19091171; Offset : -4312739320
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=192 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=193 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=194 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=195 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=196 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001070a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=197 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=198 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001070a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=199 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=200 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1957): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=201 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=202 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 7121): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] is available
,I/jxcore-log( 7121): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT4998","peerAvailable":true}]
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Found peer : motorola-XT1072_PT4998, Available: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): startWithNextDevice
I/jxcore-log( 7121): 
I/jxcore-log( 7121): device[3]: 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:56.392Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:56.392Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:16:56.392Z SendDataConnector.js: do connect now
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7121): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 831)
,W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=203 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505434323730222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] already in the list, will not add again,
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=204 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010b000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=205 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 120001100a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 120001100a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 120001100a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=207 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=208 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=209 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=210 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=211 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 1
,W/bt-sdp  ( 3823): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3823): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3823): invalid rfc slot id: 10
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 831)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Maximum number of allowed retries (0) reached, giving up... (thread ID: 831)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Exiting thread (thread ID: 831)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/jxcore-log( 7121): 2015-12-23T02:17:02.876Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] failed
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:02.876Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] failed
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:02.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7121): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): shutdown (thread ID: 831)
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=528938887, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1974294b type 2 when 594552 android} when 594552
D/[Concierge]Service( 2599): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=528938887 [*alarm*], flags=0x0
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=212 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=214 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001050a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=215 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=216 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=217 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully,
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01],
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01],
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=219 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=220 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=221 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=222 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 598319257743; DSPS: 19746619; Offset : -4312728311
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=224 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=225 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=226 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a226d6f746f726f6c612d5854313037325f505434393938222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState,{ when=-12ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-29ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-29ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-29ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-31ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-31ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-31ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=227 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010c0a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=228 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505436303638222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=229 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505436343330222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068],
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,I/jxcore-log( 7121): 2015-12-23T02:17:07.879Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05,
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:07.881Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 7121): 2015-12-23T02:17:12.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:12.889Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:12.901Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:12.901Z SendDataConnector.js: do connect now
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7121): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7121): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=230 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=231 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010c0a436f72646f7661703270c00c000c01
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3823): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3823): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3823): invalid rfc slot id: 11
W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=232 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=233 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=234 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=235 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=236 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=237 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 1
,W/bt-sdp  ( 3823): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3823): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3823): invalid rfc slot id: 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Maximum number of allowed retries (0) reached, giving up... (thread ID: 833)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Exiting thread (thread ID: 833)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): shutdown (thread ID: 833)
,I/jxcore-log( 7121): 2015-12-23T02:17:25.865Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] failed
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:25.875Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] failed
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:25.876Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7121): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=238 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 618322529403; DSPS: 20402087; Offset : -4312752550
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=239 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=240 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=241 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=,139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=242 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
,I/jxcore-log( 7121): 2015-12-23T02:17:30.877Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:30.878Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=243 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=244 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=245 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=246 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437373730222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7770","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770] already in the list, will not add again
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=247 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6800010d000a436f72646f7661703270c00c000c01527b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f505436353435222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 7121): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 7121): 2015-12-23T02:17:35.883Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:35.884Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:35.885Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:35.885Z SendDataConnector.js: do connect now
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7121): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 835)
,W/LGMDMUISystemServiceAdapter( 7121): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7121): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3823): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2736): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=248 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7770]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/jxcore-log( 7121): timeout now
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 7121): 
I/jxcore-log( 7121): sendReportNow
I/jxcore-log( 7121): 
I/jxcore-log( 7121): done, now sending data to server
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:37.168Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7121): 
,D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 7121): 2015-12-23T02:17:37.175Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=249 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010e0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=250 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3823): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
,W/bt-btm  ( 3823): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3823): btm_acl_created hci_handle=5 link_role=1  transport=1
,W/bt-btm  ( 3823): btm_acl_created hci_handle=5 link_role=1  transport=1
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3823): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3823): btm_read_remote_version_complete: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3823): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 0: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3823): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 1: BDA: 44-80-eb-7b-5a-05
W/bt-btif ( 3823): info:x10
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3823): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3823): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3823): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x0049,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x0049,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3823): process_service_search_attr_rsp
W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0047
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3823): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 21
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=251 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
W/bt-btm  ( 3823): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3823): btm_acl_role_changed: New role: 1
,W/bt-l2cap( 3823): l2c_link_hci_conn_req:current link_role= 0
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=252 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
W/bt-btm  ( 3823): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3823): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3823): btm_acl_created hci_handle=4 link_role=1  transport=1
,W/bt-btm  ( 3823): btm_acl_created hci_handle=4 link_role=0  transport=1
,W/bt-btm  ( 3823): btm_read_remote_version_complete: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3823): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3823): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3823): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3823): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3823): Entering PendingCommandState State
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 0: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3823): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3823): btm_process_remote_ext_features_page 1: BDA: b0-c5-59-3f-75-69
W/bt-btif ( 3823): info:x10
W/bt-btm  ( 3823): BTM_SwitchRole BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3823): Requested New Role: 0
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3823): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3823): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3823): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL connected => AclLinkCount = 2
,W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3823): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3823): L2CA_ErtmConnectRsp()  CID: 0x0049  Result: 0  Status: 0  BDA: b0c5593f7569  p_ertm_info:0x00000000
W/bt-l2cap( 3823): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 1,peer MTU present: 0,peer MTU: 672
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothRemoteDevices( 3823): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3823): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3823): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3823): StableState(): Entering Off State
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=253 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3823): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3823): btm_acl_role_changed: New role: 0
,E/bt-btm  ( 3823): tBTM_SEC_DEV:0xa039d3e0 rs_disc_pending=1
W/bt-btif ( 3823): bta_dm_check_av:0
W/bt-btif ( 3823): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 3823): L2CA_DisconnectRsp()  CID: 0x0049
W/bt-l2cap( 3823): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 3823): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3823): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x004a,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x004a,PSM: 3,peer MTU present: 0,peer MTU: 1691
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1
W/bt-btif ( 3823): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3823): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3823): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 835)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesWritten: 77 bytes successfully written (thread ID: 836)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Outgoing connection initialized (*handshake* thread ID: 836)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Exiting thread (thread ID: 835)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Entering thread (ID: 836)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): onBytesRead: Read 81 bytes successfully (thread ID: 836)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7121): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Exiting thread (ID: 836)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7121): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7121): Entering thread (ID: 837)
,D/io.jxcore.node.OutgoingSocketThread( 7121): Server socket local port: 41101
,I/io.jxcore.node.OutgoingSocketThread( 7121): Now accepting connections...
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 638325122988; DSPS: 21057532; Offset : -4312753010
,I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3823): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3823): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3823): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3823): Entering PendingCommandState State
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=254 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1957): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/io.jxcore.node.ConnectionHelper( 7121): onListeningForIncomingConnections: Outgoing connection is using port 41101 (peer ID: 44:80:EB:7B:5A:05)
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=255 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=256 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,I/jxcore-log( 7121): 2015-12-23T02:17:46.848Z SendDataConnector.js: CLIENT connected to 41101, error: null
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:46.848Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7121): 
I/io.jxcore.node.OutgoingSocketThread( 7121): Incoming data from address: /127.0.0.1, port: 41101
D/io.jxcore.node.OutgoingSocketThread( 7121): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7121): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7121): Exiting thread (ID: 837)
I/BluetoothBondStateMachine( 3823): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothRemoteDevices( 3823): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3823): Failed to remove device: B0:C5:59:3F:75:69
I/BluetoothBondStateMachine( 3823): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
I/BluetoothBondStateMachine( 3823): StableState(): Entering Off State
,I/jxcore-log( 7121): 2015-12-23T02:17:46.873Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7121): 
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 838, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 839, name: Receiver)
,W/bt-btm  ( 3823): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-l2cap( 3823): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3823): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3823): L2CA_ErtmConnectRsp()  CID: 0x004a  Result: 0  Status: 0  BDA: b0c5593f7569  p_ertm_info:0x00000000
W/bt-l2cap( 3823): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3823): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x004e,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3823): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3823): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x004e,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3823): new conn_srvc id:26, app_id:255
W/bt-btif ( 3823): new conn_srvc id:26, app_id:255 count:2
W/bt-btif ( 3823): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3823): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Incoming connection initialized (thread ID: 840)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Entering thread (ID: 840)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): onBytesRead: Read 82 bytes successfully (thread ID: 840)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): onBytesWritten: 77 bytes successfully written (thread ID: 840)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): removeThreadFromList: Removing thread with ID 840
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Handshake thread disposed (thread ID: 840)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7121): Exiting thread (ID: 840)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/io.jxcore.node.ConnectionHelper( 7121): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 7121): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7121): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], created successfully
D/io.jxcore.node.ConnectionHelper( 7121): onConnected: The total number of connections is now 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/io.jxcore.node.IncomingSocketThread( 7121): Entering thread (ID: 841)
I/io.jxcore.node.IncomingSocketThread( 7121): Local host address: localhost/127.0.0.1, port: 58226
D/io.jxcore.node.IncomingSocketThread( 7121): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7121): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 7121): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7121): Exiting thread (ID: 841)
I/jxcore-log( 7121): 2015-12-23T02:17:47.611Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7121): 
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29928
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 843, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7121): Entering thread (ID: 842, name: Sender)
D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22998
,I/jxcore-log( 7121): 2015-12-23T02:17:47.642Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:47.724Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7121): 
,D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13098
,I/jxcore-log( 7121): 2015-12-23T02:17:47.774Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7121): 
D/        ( 3823): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6168
,I/jxcore-log( 7121): 2015-12-23T02:17:47.886Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:47.946Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.063Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.093Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7121): ,
,I/jxcore-log( 7121): 2015-12-23T02:17:48.103Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.124Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.175Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.187Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.194Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.203Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.208Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.218Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.224Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.225Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7121): 
I/jxcore-log( 7121): oneRoundDownNow
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.225Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.225Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7121): 
D/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.IncomingSocketThread( 7121): close
D/io.jxcore.node.IncomingSocketThread( 7121): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 839
D/io.jxcore.node.IncomingSocketThread( 7121): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 838
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 838, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7121): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 839, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7121): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 838, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 839, name: Receiver)
I/jxcore-log( 7121): 2015-12-23T02:17:48.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.243Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 7121): 
,W/bt-rfcomm( 3823): rfc_port_closed
,W/bt-btif ( 3823): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
I/jxcore-log( 7121): 2015-12-23T02:17:48.252Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.282Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.303Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.322Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.326Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 7121): 
W/bt-l2cap( 3823): L2CA_DisconnectReq()  CID: 0x0048
W/bt-l2cap( 3823): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,I/jxcore-log( 7121): 2015-12-23T02:17:48.363Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.401Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.422Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.451Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.472Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.479Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.511Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): 2015-12-23T02:17:48.522Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:17:48.551Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7121): 
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3823): invalid rfc slot id: 7
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 843, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7121): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 841
D/io.jxcore.node.IncomingSocketThread( 7121): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 843
D/io.jxcore.node.IncomingSocketThread( 7121): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7121): doStop: Thread ID: 842
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7121): Either failed to read from the output stream or write to the input stream (thread ID: 842, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7121): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7121): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7121): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7121): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7121): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 842, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7121): Exiting thread (ID: 843, name: Receiver)
I/jxcore-log( 7121): 2015-12-23T02:17:48.650Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7121): 
W/bt-rfcomm( 3823): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-l2cap( 3823): L2CA_DisconnectRsp()  CID: 0x004a
W/bt-l2cap( 3823): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
W/bt-rfcomm( 3823): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 3823): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3823): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -3
,I/BluetoothMapService( 3823): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3823): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3823): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3823): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3823): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3823): state: -2147483648
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4598): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4598): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/bt-btm  ( 3823): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3823): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -4
,I/BluetoothMapService( 3823): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3823): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3823): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3823): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3823): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3823): state: -2147483648
D/LGBluetoothPowerSaveListener( 7199): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4598): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4598): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=257 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=258 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=259 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=260 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WfdsMonitor( 1957): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=261 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010e0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=262 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=263 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376b8
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376b8: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7121): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service request added successfully
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=264 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=265 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service discovery started successfully
I/wpa_supplicant( 2736): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1957): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=266 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1957): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=528938887, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2599): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=528938887 [*alarm*], flags=0x0
,I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=267 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2736): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1957): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=268 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2736): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7121): teardown
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): testSendData stopped
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7121): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7121): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7121): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7121): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707433393131222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2736): P2P-FIND-STOPPED 
D/WfdsMonitor( 1957): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=269 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7121): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7121): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7121): setState: NOT_STARTED
I/jxcore-log( 7121): StopBroadcasting went ok
I/jxcore-log( 7121): 
I/jxcore-log( 7121): 2015-12-23T02:18:03.711Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7121): 
I/io.jxcore.node.ConnectionHelper( 7121): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7121): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7121): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7121): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7121): onDiscoveryManagerStateChanged: NOT_STARTED
,I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7121): ****TEST TOOK:  ms ****
I/jxcore-log( 7121): 
I/jxcore-log( 7121): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7121): 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 658327848502; DSPS: 21712981; Offset : -4312743458
,D/AndroidRuntime( 7965): 
D/AndroidRuntime( 7965): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7965): CheckJNI is OFF
D/AndroidRuntime( 7965): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 7121:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1037): Skipping PackageSetting{158b24b7 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{28765d2d u0 com.test.thalitest/.MainActivity t4}
,W/InputDispatcher( 1037): channel 'e8d34f8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1037): channel 'e8d34f8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
D/WifiService( 1037): Client connection lost with reason: 4
I/WindowState( 1037): WIN DEATH: Window{e8d34f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher( 1037): Attempted to unregister already unregistered input channel 'e8d34f8 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,D/InputDispatcher( 1037): Window went away: Window{e8d34f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/GBMv2   (  337): DFP En is all cleared set to be enabled
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{28765d2d u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{28765d2d u0 com.test.thalitest/.MainActivity t4 f}
,I/art     ( 4598): Explicit concurrent mark sweep GC freed 33204(1602KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 633us total 40.447ms
,I/[LGHome]EVENT( 2076): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2076): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2076): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1957): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1957): topRunningActivity=ActivityInfo{2dfa616f co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1913): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2076): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2076): [Launcher.java:1056:onResume()]onResume end
,D/LIA_Informant_ActionManagerMessageHandler( 2684): handleMessage: what(1000) actionID(0x1000003)
D/SplitWindowPolicy( 1957): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2076): [Launcher.java:1114:onPause()]onPause
D/SplitWindowPolicy( 1957): topRunningActivity=ActivityInfo{28257e7c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1913): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 2684): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2684): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2076): , create_time: 1430558575574
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2076): , create_time: 1430558575600
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1450367114146
I/GBoardWebViewUtils( 2076): , create_time: 1450367114951
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
D/WallpaperManager( 2076): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@10021401,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1826): Ignoring removeGeofence because network location is disabled.
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,E/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2032): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2684): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/PostponalbeReceiver( 6639): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/System.err( 4553): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4553): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4553): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4553): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4553): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4553): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4553): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4553): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4553): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4553): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 2076): Background sticky concurrent mark sweep GC freed 3362(166KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 5.161ms total 17.945ms
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 43942(2MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.738ms total 171.604ms
I/art     ( 1037): WaitForGcToComplete blocked for 157.785ms for cause Explicit
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7999 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1444): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2076): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/administrator( 1037): Handling package changes for user 0
,D/SplitUIManager( 1879): split_name #11 / not available #0
D/SplitUIService( 1879): removed split : 
I/LockScreenSettings( 7999): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3823): [BTUI] [-] updateMediaPlayerInfo
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1444): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/AppUp4:PreloadHelper( 7366): added Exclude : com.test.thalitest
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
,I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3147): Thermal-Lib-Client: Client request sent
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8021 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{309e314e u0 com.lge.launcher2/.Launcher t3} time:659336
D/KeyguardModel( 1444): handleShortcutListChanged...
,I/[Concierge]WidgetView( 2076): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2599): onStartCommand(). Type : 8
D/[Concierge]Service( 2599): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2599): Update widget ID : 11
D/[Concierge]WidgetView( 2076): change position of spinner
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/[Concierge]Service( 2599): onStartCommand(). Type : 0
,D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
I/[Concierge]WidgetView( 2076): initWebView(). Time : 1450837087690
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
I/ActivityManager( 1037): Killing 7417:com.lge.email/u0a23 (adj 15): empty #17
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 11309(608KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.608ms total 246.331ms
,D/KeyguardModel( 1444): handleShortcutListChanged...
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_7417/cgroup.procs: No such file or directory
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
,W/ResourcesManager( 8021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2076): Return exist ConciergeWebView. Reuse : 885313674
D/[Concierge]WidgetView( 2076): State Change : null -> AccInBeforeState
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2076): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@216cdf20
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2076): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2076): Widget kill message received. Destory myself. My : 1450836456782, New one : 1450837087690
D/[Concierge]WidgetView( 2076): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2076): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,D/[Concierge]WidgetView( 2076): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/SystemConfig( 8021): BUILD Country: EU
I/SystemConfig( 8021): BUILD Operator: OPEN
I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7965): Shutting down VM
,I/Timeline( 2076): Timeline: Activity_idle id: android.os.BinderProxy@3a166eee time:659531
I/ActivityManager( 1037): Killing 7462:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7462/cgroup.procs: No such file or directory
,I/SystemConfig( 8021): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8021): existFile = false
I/SystemConfig( 8021): canReadFile = false
I/SystemConfig( 8021): systemFeature RCS result false
D/SystemConfig( 8021): refreshRcsSupport() :false
D/VoicemailCleanupService( 2223): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8042 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 9.676ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.975ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.010ms
,W/ResourcesManager( 8042): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8042): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8042): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8042): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2076): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/LGEmail ( 8042): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8042): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 8042): No package identifier when getting value for resource number 0x00000000
,I/GBoardtInterface( 2076): onReloaded()
I/GBoardWebViewClient( 2076): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 2684): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2684): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2684): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2684): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2684): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2684): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2684): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2684): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2684): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LgDataFeature( 8042): LgDataFeature() Constructor: none
D/LgDataFeature( 8042): LgDataFeature() Constructor Done, null
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,I/PackageChangeReceiver( 8042): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8065 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 7486:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10057/pid_7486/cgroup.procs: No such file or directory
,W/ResourcesManager( 8065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8065): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8065): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8065): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 8065): Total System Memory = 2995761152
,I/GBoardtInterface( 2076): exportHTML()
D/SystemHelper( 8065): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 8065): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1037): Killing 7507:com.lge.drmservice/u0a62 (adj 15): empty #17

```
