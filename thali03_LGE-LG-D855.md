#### Test 55742142a5c2fdb_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277460586385; DSPS: 9233245; Offset : -4328271357
,D/AndroidRuntime( 7188): 
D/AndroidRuntime( 7188): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7188): CheckJNI is OFF
D/AndroidRuntime( 7188): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1968): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{c92de34 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{c92de34 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7207 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7188): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1875): Display #0 changed.
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{1863817c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{15ba1a05 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7207): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7207): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7207): Loading: webviewchromium
I/LibraryLoader( 7207): Time to load native libraries: 4 ms (timestamps 2577-2581)
I/LibraryLoader( 7207): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7207): Binding Chromium to main looper Looper (main, tid 1) {3fd2102c}
I/LibraryLoader( 7207): Expected native library version number "",actual native library version number ""
I/chromium( 7207): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7207): Initializing chromium process, renderers=0
W/art     ( 7207): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  315): registerClient() client 0xb1231160, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@372ce91e:true
W/chromium( 7207): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7207): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7207): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7207): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7207): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7207): Build Date: 12/12/14 금
I/Adreno-EGL( 7207): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7207): Remote Branch: 
I/Adreno-EGL( 7207): Local Patches: 
I/Adreno-EGL( 7207): Reconstruct Branch: 
W/chromium( 7207): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7207): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7207): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7207): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7207): CordovaWebView is running on device made by: LGE
W/art     ( 7207): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7207): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{2a74a45d u0 com.test.thalitest/.MainActivity t4}
D/LgDataFeature( 7207): LgDataFeature() Constructor: none
D/LgDataFeature( 7207): LgDataFeature() Constructor Done, null
I/art     ( 1037): Explicit concurrent mark sweep GC freed 25728(1145KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.434ms total 105.008ms
D/OpenGLRenderer( 7207): Render dirty regions requested: true
I/OpenGLRenderer( 7207): Initialized EGL, version 1.4
D/OpenGLRenderer( 7207): Enabling debug mode 0
D/Atlas   ( 7207): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{87b13e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@244d8989,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +746ms (total +840ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{2a74a45d u0 com.test.thalitest/.MainActivity t4} time:283108
I/Timeline( 7207): Timeline: Activity_idle id: android.os.BinderProxy@2d8fdc5c time:283123
I/chromium( 7207): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7207): 
D/JsMessageQueue( 7207): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7207): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7207): 
D/jxcore_app_log( 7207): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435102976
,D/JX-Cordova( 7207): jxcore cordova android initializing
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7207): Initializing JXcore engine
W/jxcore-log( 7207): JXcore engine is ready
W/jxcore-log( 7207): Starting JXcore engine
,W/.test.thalitest( 7207): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8364]" dev="sockfs" ino=8364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7207): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7207): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10358]" dev="sockfs" ino=10358 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7207): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7207): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33963]" dev="sockfs" ino=33963 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 7207): Platform android
W/jxcore-log( 7207): 
W/jxcore-log( 7207): Process ARCH arm
W/jxcore-log( 7207): 
,I/art     ( 7207): Background sticky concurrent mark sweep GC freed 125008(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.650ms total 139.201ms
I/jxcore-log( 7207): JXcore Cordova bridge is ready!
I/jxcore-log( 7207): 
W/jxcore-log( 7207): JXcore engine is started
,I/jxcore-log( 7207): Toggling radios to true
I/jxcore-log( 7207): 
,D/BluetoothAdapter( 7207): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7207, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7207, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7207, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=7207, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7207): Radios toggled
I/jxcore-log( 7207): 
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7207): Received device characteristics:
I/jxcore-log( 7207): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7207): Bluetooth name: G3-1
I/jxcore-log( 7207): Device name: LGE-LG-D855
I/jxcore-log( 7207): 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7207): Perf Test app loaded loaded
I/jxcore-log( 7207): 
E/WifiNative: ( 1037): [286,733,065 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/jxcore-log( 7207): check test folder
I/jxcore-log( 7207): 
I/jxcore-log( 7207): found test : ./testFindPeers.js
I/jxcore-log( 7207): 
I/jxcore-log( 7207): found test : ./testSendData.js
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7279 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/CommandListener(  310): Clearing all IP addresses on wlan0
V/NativeCrypto( 2143): Read error: ssl=0xaf4d1200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2143): SSL shutdown failed: ssl=0xaf4d1200: I/O error during system call, Broken pipe
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1968): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [286,900,330 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286905
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286906
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  310): Clearing all IP addresses on wlan0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286937  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286939  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286949  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1459): refres,hViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1875): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/ResourcesManager( 7279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
W/ResourcesManager( 7279): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 7279): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
W/ResourcesManager( 7279): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
I/chromium( 7207): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7207): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7279): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7279): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7279): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7279): [AUTORUN] setTetherStatus() : status=false
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-186ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6755:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6755/cgroup.procs: No such file or directory
,I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7279): LgDataFeature() Constructor: none
D/LgDataFeature( 7279): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7344 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6161:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6161/cgroup.procs: No such file or directory
,W/ResourcesManager( 7344): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7344): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7344): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7344): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7344): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7344): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7344): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7344): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7344): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 7344): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 7344): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false,
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7344): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7344): LgDataFeature() Constructor: none
,D/LgDataFeature( 7344): LgDataFeature() Constructor Done, null
V/SoundPool( 7344): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7344): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7344): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7344): doLoad: loading sample sampleID=1
,I/QRemote ( 7344): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7344): Start decode
V/MediaPlayer[Native]( 7344): decode(31, 10857164, 17813)
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1163ac0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/QRemote ( 7344): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6918): QS Service created
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7344): Create singleton instance
,V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
,I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b100 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b150 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b1a0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b1f0 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b240 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b740 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b7e0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b880 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb1163ac0, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb1163ac0, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
,V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971251264
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971252544
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971252704
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971252864
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b7e0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b740 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119b240 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb119bc90 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
,V/AudioCache(  315): notify(0xb1163ac0, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae504000, 0xb153f000, 4096)
,V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae505000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae506000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae507000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae508000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae509000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50a000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50b000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50c000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50d000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50e000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae50f000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae510000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae511000, 0xb153f000, 4096)
I/UEI.SmartControl( 6918): Service initServices...
D/UEI.SmartControl( 6918): QS start get config
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae512000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae513000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae514000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae515000, 0xb153f000, 4096)
,V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae516000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae517000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae518000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae519000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51a000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51b000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51c000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51d000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51e000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae51f000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae520000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae521000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae522000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae523000, 0xb153f000, 4096)
,V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae524000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae525000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae526000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae527000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae528000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae529000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52a000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52b000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52c000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52d000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52e000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae52f000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae530000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae531000, 0xb153f000, 4096)
,V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae532000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae533000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae534000, 0xb153f000, 4096)
V/AudioCache(  315): write(0xb153f000, 4096)
V/AudioCache(  315): memcpy(0xae535000, 0xb153f000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb153f000, 280)
V/AudioCache(  315): memcpy(0xae536000, 0xb153f000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb1163ac0, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb1163ac0, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1163ac0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b1f0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b1a0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b150 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b100 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119bc90 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b240 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b740 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb119b7e0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 7344): close(31)
V/SoundPool( 7344): pointer = 0x9ff44000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7344): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7344): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8192
,I/UEI.SmartControl( 6918): Supports setup maps: true
,D/UEI.SmartControl( 6918): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6918): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6918): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6918): ### init IR Blaster...
,D/serial_port( 6918): Configuring serial port
E/UEI.SmartControl( 6918): UEIBLaster setting for 616
,I/UEI.SmartControl( 6918): Setting serial record hearder size = 2
I/UEI.SmartControl( 6918): configuring settings for MAXQ616
I/UEI.SmartControl( 6918): Get version...
D/UEI.SmartControl( 6918): serial port data available: 21
,D/UEI.SmartControl( 6918): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6918): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6918): QS saving settings...
D/UEI.SmartControl( 6918): IR Blaster version: 25672567
,D/UEI.SmartControl( 6918): serial port data available: 4
,W/ContextImpl( 6918): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6918): Device manager: loading config....
E/UEI.SmartControl( 6918): Services init done
D/UEI.SmartControl( 6918): QS Service init finished
D/UEI.SmartControl( 6918): ----------- loading internal config...
D/UEI.SmartControl( 6918): QS Service version name: 2.1.91
D/UEI.SmartControl( 6918): QS Service version code: 201091
D/UEI.SmartControl( 6918): Service requested: Control
,D/UEI.SmartControl( 6918): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6918): Internal service binding...
I/QRemote ( 7344): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
E/UEI.SmartControl( 6918): Loading SETTINGS...
I/UEI.SmartControl( 6918): ------ IControl API: 11
D/UEI.SmartControl( 6918): File observer start...
E/UEI.SmartControl( 6918): IR Port is disabled: false
D/UEI.SmartControl( 6918): Starting file observer...
,I/UEI.SmartControl( 6918): Registering callback...
I/UEI.SmartControl( 6918): ------ IControl API: 19
I/UEI.SmartControl( 6918): Registering Services Ready callback...
D/UEI.SmartControl( 6918): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6918): Notify AllClients services are ready: 0
,I/QRemote ( 7344): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7344): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7344): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7344): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/UEI.SmartControl( 6918): -----service ready thread exits
D/QRemote ( 7344): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6918): ------ IControl API: 8
D/QRemote ( 7344): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7344): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7344): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7344): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7344): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7344): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7344): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7344): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452601167859]
D/QRemote ( 7344): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6185:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7344): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6185/cgroup.procs: No such file or directory
,V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7344): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2698): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289039  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289060  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2698): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289151  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2698): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289152  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289163
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289163
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
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289168
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289168
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289168
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289170  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289190  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289195  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289195  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289196
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289196
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7279): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7279): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7279): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7279): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7279): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
,D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289289  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289290  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289293  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289293  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289294  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e2c5e60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e2c5e60 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
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
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
,D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1968): handleWifiStateChangedEvent: 1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  310): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state:, CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
W/dsqn    ( 7420): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7420): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
E/DSQN    ( 7420): DSQN ssw
,D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7344): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7344): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7344): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7344): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7279): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 12:19:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452601168853], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452601168833]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1875): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7426): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7426): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7279): MCCMNC not supported: null
D/QRemote ( 7344): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7344): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7344): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7344): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/dhcpcd  ( 7426): version 5.5.6 starting
I/QRemote ( 7344): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
E/dhcpcd  ( 7426): get_duid: m
D/dhcpcd  ( 7426): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7426): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7426): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7426): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7426): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7426): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7426): wlan0: sending REQUEST (xid 0xe07e9ed9), next in 4.09 seconds
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2076ece1 type 2 when 289882 com.google.android.gms} when 289882
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5911): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5911): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7464 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 533us total 21.949ms
,D/GCM     ( 2143): Connected
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 20.679ms
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 20.073ms
,D/GCM     ( 2143): Message class com.google.f.a.a.p
I/AppUp4:AppBoxCP( 7464): onCreate
W/AppUp4:DB( 7464):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7464):  setFingerPrint start
,I/AppUp4:DB( 7464):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7464):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7464):  SDK version = 21
,I/AppUp4:DB( 7464):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7464): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7464): onReceive
,D/LgDataFeature( 7464): LgDataFeature() Constructor: none
D/LgDataFeature( 7464): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7464): Context : android.app.ReceiverRestrictedContext@3297308a
D/AppUp4:CustFacade( 7464): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7464): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7464): begin check event
I/AppUp4:CustModeStarterReceiver( 7464): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7464): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7464): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7464): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7464): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6777:com.lge.email/u0a23 (adj 15): empty #17
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6777/cgroup.procs: No such file or directory
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3372): DownloadService onCreate
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3372): in removeSpuriousFiles
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@2cb9c8e on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3372): in trimDatabase
,V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@2368b8bc on behalf of 3372
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7496 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3372): DownloadService onStartCommand
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@37e8f39a on behalf of 3372
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
,V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
V/DownloadManager( 3372): DownloadService onDestroy
,W/ResourcesManager( 7496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7496): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7496): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7496): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524295
I/LGEmail ( 7496): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7496): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7496): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7496): LgDataFeature() Constructor: none
D/LgDataFeature( 7496): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7426): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/eas_req ( 7496): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 7426): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7426): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7426): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7426): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7426): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7426): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7426): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7426): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7524 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7496): JNI_OnLoad()
I/HubEmail( 7496): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7496): registerNatives()
I/HubEmail( 7496): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7496): registerNativeMethods()
I/HubEmail( 7496): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7496): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1037): Killing 6222:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6222/cgroup.procs: No such file or directory
,W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7575 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
,D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7524): There are no updated forms. The schedule will be deleted.
V/FormManager( 7524): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1037): Killing 6641:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6641/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7602 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6814:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6814/cgroup.procs: No such file or directory
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7207): BLE is supported
I/jxcore-log( 7207): 
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7619 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6867:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6867/cgroup.procs: No such file or directory
,I/art     ( 7619): Almond Protected OAT
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/WeatherApplication( 7619): removeAccount
D/WeatherApplication( 7619): Account.length = 0
E/WeatherApplication( 7619): OPERATOR:OPEN
,D/WeatherAncestor( 7619): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:31
D/Weather.Utils( 7619): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7619): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7619): 2 : This is isUpdating : false
,D/WeatherAncestor( 7619): connectivity changed - connection : true
D/WeatherService( 7619): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7619): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7619): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7619): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7619): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7619): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:31
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7637 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6955:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6955/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7637): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7637): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7637): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7637): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5911): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7637): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7637): Loading: webviewchromium
,I/LibraryLoader( 7637): Time to load native libraries: 6 ms (timestamps 2571-2577)
I/LibraryLoader( 7637): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7637): Binding Chromium to main looper Looper (main, tid 1) {36a421d}
,I/LibraryLoader( 7637): Expected native library version number "",actual native library version number ""
I/chromium( 7637): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7637): Initializing chromium process, renderers=0
,W/art     ( 7637): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7637): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7637): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7637): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb1427260, uid 10093
W/AudioManagerAndroid( 7637): Requires BLUETOOTH permission
I/Adreno-EGL( 7637): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7637): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7637): Build Date: 12/12/14 금
I/Adreno-EGL( 7637): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7637): Remote Branch: 
I/Adreno-EGL( 7637): Local Patches: 
I/Adreno-EGL( 7637): Reconstruct Branch: 
,I/NSApplication( 7637): Starting up...
,I/ActivityManager( 1037): Killing 6980:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6980/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7464): onReceive
D/AppUp4:CustFacade( 7464): Context : android.app.ReceiverRestrictedContext@3297308a
D/AppUp4:CustFacade( 7464): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7464): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7464): begin check event
I/AppUp4:CustModeStarterReceiver( 7464): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3372): DownloadService onCreate
,I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@33cf7bc1 on behalf of 3372
V/DownloadManager( 3372): DownloadService onStartCommand
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@3689f2a7 on behalf of 3372
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@14d56354 on behalf of 3372
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3372): processing inserted download 1
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3372): processing inserted download 4
V/DownloadManager( 3372): processing inserted download 7
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3372): processing inserted download 8
V/DownloadManager( 3372): processing inserted download 9
W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3372): processing inserted download 17
,V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = false
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3372): DownloadService onDestroy
D/WeatherAncestor( 7619): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:32
D/Weather.Utils( 7619): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7619): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7619): 2 : This is isUpdating : false
D/WeatherAncestor( 7619): connectivity changed - connection : true
D/WeatherService( 7619): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12660318
D/ForecastDataCache( 7619): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7619): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7619): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7619): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7619): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:32
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
W/ResourcesManager( 1420): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1420): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7464): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7464): onReceive
D/AppUp4:CustFacade( 7464): Context : android.app.ReceiverRestrictedContext@3297308a
D/AppUp4:CustFacade( 7464): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7464): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7464): begin check event
I/AppUp4:CustModeStarterReceiver( 7464): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3372): DownloadService onCreate
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@4a5bf2 on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@16d91243 on behalf of 3372
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3372): DownloadService onStartCommand
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@229e453e on behalf of 3372
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
,V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
I/art     ( 1037): Explicit concurrent mark sweep GC freed 83651(3MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.848ms total 96.307ms
,W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7524): There are no updated forms. The schedule will be deleted.
V/DownloadManager( 3372): DownloadService onDestroy
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/FormManager( 7524): Alarm would be updated, because LastCheckTime has been updated.
,E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/Settings( 7496): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3343): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3343): networkInfo.isConnected() = true
D/PhoneState( 3343): setPdpRejectCasuse : false
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7619): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:32
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/Weather.Utils( 7619): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7619): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7619): 2 : This is isUpdating : false
D/WeatherAncestor( 7619): connectivity changed - connection : true
D/WeatherService( 7619): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@12660318
D/ForecastDataCache( 7619): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7619): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7619): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7619): 2 : isUpdateNeedForAlarm : no city return false
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
D/WeatherAncestor( 7619): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:32
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,V/FormManager( 7524): There are no updated forms. The schedule will be deleted.
V/FormManager( 7524): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6918): Internal timer expired: 2
D/UEI.SmartControl( 6918): unbind internal service
,D/serial_port( 6918): close(fd = 24)
,I/UEI.SmartControl( 6918): Serial port is closed.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7207): Connected to the server!
I/jxcore-log( 7207): 
,I/chromium( 7207): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/GAV4    ( 7637): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297463104735; DSPS: 9888688; Offset : -4328284299
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{32a323b9 type 2 when 297497 android} when 297497
,V/QRemote ( 7344): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7344): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8192
,I/BooksSync( 7065): Starting books sync
,D/BooksSync( 7065): started syncMyEbooks
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
,W/ApiaryClient( 7065): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5609906940317859881&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
,W/ApiaryClient( 7065): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5609906940317859881&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
,W/ApiaryClient( 7065): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5609906940317859881&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
E/BooksSync( 7065): Soft error: 
E/BooksSync( 7065): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5609906940317859881&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7065): Headers:
E/BooksSync( 7065): accept-encoding: [gzip]
E/BooksSync( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7065): gdata-version: 2
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7065): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7065): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7065): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7065): {
E/BooksSync( 7065):  "error": {
E/BooksSync( 7065):   "errors": [
E/BooksSync( 7065):    {
E/BooksSync( 7065):     "domain": "global",
E/BooksSync( 7065):     "reason": "required",
E/BooksSync( 7065):     "message": "Login Required",
E/BooksSync( 7065):     "locationType": "header",
E/BooksSync( 7065):     "location": "Authorization"
E/BooksSync( 7065):    }
E/BooksSync( 7065):   ],
E/BooksSync( 7065):   "code": 401,
E/BooksSync( 7065):   "message": "Login Required"
E/BooksSync( 7065):  }
E/BooksSync( 7065): }
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7065): 	... 8 more
,E/BooksSync( 7065): Sync error
E/BooksSync( 7065): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5609906940317859881&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7065): Headers:
E/BooksSync( 7065): accept-encoding: [gzip]
E/BooksSync( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7065): gdata-version: 2
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7065): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7065): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7065): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7065): {
E/BooksSync( 7065):  "error": {
E/BooksSync( 7065):   "errors": [
E/BooksSync( 7065):    {
E/BooksSync( 7065):     "domain": "global",
E/BooksSync( 7065):     "reason": "required",
E/BooksSync( 7065):     "message": "Login Required",
E/BooksSync( 7065):     "locationType": "header",
E/BooksSync( 7065):     "location": "Authorization"
E/BooksSync( 7065):    }
E/BooksSync( 7065):   ],
E/BooksSync( 7065):   "code": 401,
E/BooksSync( 7065):   "message": "Login Required"
E/BooksSync( 7065):  }
E/BooksSync( 7065): }
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7065): 	... 8 more
I/BooksSync( 7065): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297497, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317465041862; DSPS: 10544111; Offset : -4328271629
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=205228531, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{21206d6a type 2 when 327532 android} when 327532
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=205228531 [*alarm*], flags=0x0
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337467368208; DSPS: 11199547; Offset : -4328264671
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357469258878; DSPS: 11854969; Offset : -4328266142
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6302): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6302): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6302): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6302): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6302): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6302): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6302): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6302): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377471264027; DSPS: 12510395; Offset : -4328275128
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=205228531, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=205228531 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397473304957; DSPS: 13165822; Offset : -4328278823
,I/jxcore-log( 7207): --- start :testFindPeers.js---
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): testFindPeers created [object Object]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): serverPort is 8876
I/jxcore-log( 7207): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7207): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3835): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): start: OK
I/io.jxcore.node.ConnectionHelper( 7207): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7207): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7207): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7207): start: OK
I/jxcore-log( 7207): StartBroadcasting started ok
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7207): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7207): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1968): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=55 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417475157553; DSPS: 13821243; Offset : -4328287696
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
,D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1968): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
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
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
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
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7207): 
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000102000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000102000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000102000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7207): 
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7207): 
I/[SystemUI]LGPowerUI( 1459): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1459): On Skip Timer : true
,D/LEDHandler( 1968): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1968): Battery Level Remaining: 100%
D/LEDHandler( 1968): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1459): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1459): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3835): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1459): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437477182441; DSPS: 14476669; Offset : -4328277124
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2698): P2P-FIND-STOPPED 
D/WfdsMonitor( 1968): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457479201496; DSPS: 15132095; Offset : -4328272204
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=71 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G4-1
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
,I/jxcore-log( 7207): 
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=75 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
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
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear servic,e request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000104000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000104000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000104000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 7207): ,
I/jxcore-log( 7207): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7207): 
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477481109875; DSPS: 15787518; Offset : -4328286405
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=87 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=88 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=90 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001070a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=93 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.and,roid.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=95 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=96 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=99 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497482884242; DSPS: 16442936; Offset : -4328282006
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=100 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=101 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=103 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: G4-1
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
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [,08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=110 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=111 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler },
,E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000106000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000106000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000106000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027,
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=113 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 7207): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7207): 
I/jxcore-log( 7207): timeout now
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): weAreDoneNow
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): done, now sending data to server
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=114 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001070a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=115 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037):, InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=117 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=118 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
,I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517485225849; DSPS: 17098373; Offset : -4328290382
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=122 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=124 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=125 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=54 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=54 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=127 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=128 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
,I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=129 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=130 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
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
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=131 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 103,7): InactiveState{ when=-12ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=132 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-32ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-32ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-32ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=133 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=135 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=136 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7207): teardown
I/jxcore-log( 7207): 
I/jxcore-log( 7207): testFindPeers stopped
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2698): P2P-FIND-STOPPED 
D/WfdsMonitor( 1968): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7207): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setState: NOT_STARTED
I/jxcore-log( 7207): StopBroadcasting went ok
I/jxcore-log( 7207): 
,D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/jxcore-log( 7207): --- start :testSendData.js---
I/jxcore-log( 7207): 
I/jxcore-log( 7207): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log( 7207): 
I/jxcore-log( 7207): daya100000
I/jxcore-log( 7207): 
I/jxcore-log( 7207): check server
I/jxcore-log( 7207): 
I/jxcore-log( 7207): serverPort is 55885
I/jxcore-log( 7207): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7207): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): start: OK
I/io.jxcore.node.ConnectionHelper( 7207): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7207): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7207): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7207): start: OK
I/jxcore-log( 7207): StartBroadcasting started ok
I/jxcore-log( 7207): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
,I/jxcore-log( 7207): [ { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 7207):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 7207):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 7207):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 7207):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 7207):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 7207):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 7207):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 7207):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 7207):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 7207):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 7207):   { address: 'F8:95:C7:87:85:54', tryCount: 0 } ]
I/jxcore-log( 7207): 
I/jxcore-log( 7207): startWithNextDevice
I/jxcore-log( 7207): 
I/jxcore-log( 7207): do fake peer & start
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:28.038Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:28.038Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:28.038Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 7207): 2016-01-12T12:23:28.048Z SendDataTCPServer.js: TCP/IP server is bound to port: 55885
I/jxcore-log( 7207): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 827)
I/io.jxcore.node.ConnectionHelper( 7207): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7207): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7207): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2698): P2P-FIND-STOPPED 
D/WfdsMonitor( 1968): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=139 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7207): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: RESTARTING
I/chromium( 7207): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
,D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/chromium( 7207): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3835): [BTUI] connectSocket FD=85 mFd=84
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=2 link_role=1  transport=1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 44-80-eb-7b-5a-05
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a116b1:true
,D/LGBluetoothFeatureConfig( 7279): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7279): [BTUI] FileNotFound: readProperty
D/LGBluetoothUtils( 7279): [BTUI] FileNotFound: storeHashmapFromFile
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 1
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0040
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 4480eb7b5a05  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): Start timer timeout, starting now...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=140 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: STARTED
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7832 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3835): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3835): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
,W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
D/BluetoothManagerService( 1037): Message: 20
,D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b96df17:true
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0043,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0043,PSM: 3,peer MTU present: 0,peer MTU: 1691
E/ActivityThread( 7832): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7832): No ProfileInfo entries
I/LG Account v2.2( 7832): isEnabled: false
I/Feature ( 7832): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7832): [Lifetracker]Country: EU
I/Feature ( 7832): [Lifetracker]Operator: OPEN
I/Feature ( 7832): [Lifetracker]Ranking support: false
I/Feature ( 7832): [Lifetracker]Comfort support: false
I/Feature ( 7832): [Lifetracker]Accessory: true
I/Feature ( 7832): [Lifetracker]Health device: true
I/Feature ( 7832): [Lifetracker]Extra Pedometer: false
I/Feature ( 7832): [Lifetracker]Blood glucose device: false
I/Feature ( 7832): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 7004:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onSocketConnected: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 827)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 828)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Outgoing connection initialized (*handshake* thread ID: 828)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 827)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 828)
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_7004/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesRead: Read 65 bytes successfully (thread ID: 828)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Handshake succeeded with [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onHandshakeSucceeded: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 828)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 XT1072]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 XT1072], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7207): Entering thread (ID: 829)
D/io.jxcore.node.OutgoingSocketThread( 7207): Server socket local port: 58645
I/io.jxcore.node.OutgoingSocketThread( 7207): Now accepting connections...
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/io.jxcore.node.ConnectionHelper( 7207): onListeningForIncomingConnections: Outgoing connection is using port 58645 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 7207): 2016-01-12T12:23:34.169Z SendDataConnector.js: CLIENT connected to 58645, error: null
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:34.169Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7207): 
I/io.jxcore.node.OutgoingSocketThread( 7207): Incoming data from address: /127.0.0.1, port: 58645
D/io.jxcore.node.OutgoingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7207): Exiting thread (ID: 829)
I/jxcore-log( 7207): 2016-01-12T12:23:34.180Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7207): 
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 831, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 830, name: Sender)
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=141 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61130
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=142 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66624
,I/jxcore-log( 7207): 2016-01-12T12:23:35.686Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56724
,I/jxcore-log( 7207): 2016-01-12T12:23:35.927Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=144 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48520
,I/jxcore-log( 7207): 2016-01-12T12:23:36.287Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7207): 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1968): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=146 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproje,ct.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=147 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:37630
,I/jxcore-log( 7207): 2016-01-12T12:23:36.728Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7207): 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537486699174; DSPS: 17753781; Offset : -4328281953
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:27730
,I/jxcore-log( 7207): 2016-01-12T12:23:36.947Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7207): 
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18820
,I/jxcore-log( 7207): 2016-01-12T12:23:37.130Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7207): 
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7930
,I/jxcore-log( 7207): 2016-01-12T12:23:37.592Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:37.959Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:38.369Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7207): 
,D/btif_config_util( 3835): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 7207): 2016-01-12T12:23:38.750Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.750Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7207): 
I/jxcore-log( 7207): oneRoundDownNow
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.752Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.752Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7207): 
,D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 7207): close
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 831
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 830
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 830, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7207): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 831, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 831, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 830, name: Sender)
I/jxcore-log( 7207): 2016-01-12T12:23:38.767Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 7207): 
I/jxcore-log( 7207): ---- round done--------
I/jxcore-log( 7207): 
I/jxcore-log( 7207): startWithNextDevice
I/jxcore-log( 7207): 
I/jxcore-log( 7207): do fake peer & start
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.771Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.771Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:38.771Z Send,DataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 832)
,W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b050 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-rfcomm( 3835): rfc_port_closed
W/bt-btif ( 3835): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-btm  ( 3835): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=4 link_role=0  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
,W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-ae-67
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0041
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 2
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0042
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3835): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onSocketConnected: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 832)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Outgoing connection initialized (*handshake* thread ID: 833)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 832)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesRead: Read 66 bytes successfully (thread ID: 833)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Handshake succeeded with [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onHandshakeSucceeded: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 833)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 Nexus 5]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7207): Entering thread (ID: 834)
D/io.jxcore.node.OutgoingSocketThread( 7207): Server socket local port: 33087
I/io.jxcore.node.OutgoingSocketThread( 7207): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7207): onListeningForIncomingConnections: Outgoing connection is using port 33087 (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 7207): 2016-01-12T12:23:40.969Z SendDataConnector.js: CLIENT connected to 33087, error: null
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:40.970Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7207): 
,I/io.jxcore.node.OutgoingSocketThread( 7207): Incoming data from address: /127.0.0.1, port: 33087
D/io.jxcore.node.OutgoingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7207): Exiting thread (ID: 834)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 836, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 835, name: Sender)
,I/jxcore-log( 7207): 2016-01-12T12:23:40.994Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7207): 
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
,I/jxcore-log( 7207): 2016-01-12T12:23:42.642Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63816
,W/ProcessCpuTracker( 1037): Skipping unknown process pid 7906
,W/ProcessCpuTracker( 1037): Skipping unknown process pid 7909
I/jxcore-log( 7207): 2016-01-12T12:23:42.864Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/jxcore-log( 7207): 2016-01-12T12:23:43.118Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42036
,I/jxcore-log( 7207): 2016-01-12T12:23:43.277Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,I/jxcore-log( 7207): 2016-01-12T12:23:43.518Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01
I/jxcore-log( 7207): 2016-01-12T12:23:43.757Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 7207): 2016-01-12T12:23:44.167Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7207): 
,E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -1
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 1
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1446
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@217f6ced:true
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: XT1072
I/jxcore-log( 7207): 2016-01-12T12:23:45.186Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:45.414Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7207): 
,D/btif_config_util( 3835): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=150 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010a0a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01
I/jxcore-log( 7207): 2016-01-12T12:23:48.224Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.226Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7207): 
I/jxcore-log( 7207): oneRoundDownNow
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.227Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.228Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7207): 
,D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 7207): close
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 836
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 835
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 835, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7207): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 836, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 835, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 836, name: Receiver)
I/jxcore-log( 7207): 2016-01-12T12:23:48.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7207): 
I/jxcore-log( 7207): ---- round done--------
I/jxcore-log( 7207): 
I/jxcore-log( 7207): startWithNextDevice
I/jxcore-log( 7207): 
I/jxcore-log( 7207): do fake peer & start
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.257Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.257Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:48.257Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 837)
W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: b0c5593f7569  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=205228531, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2bfc722 type 2 when 550223 android} when 550223
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=205228531 [*alarm*], flags=0x0
,I/BooksSync( 7065): Starting books sync
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
D/BooksSync( 7065): started syncMyEbooks
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-rfcomm( 3835): rfc_port_closed
W/bt-btif ( 3835): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0043
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: b0-c5-59-3f-75-69
,W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: b0-c5-59-3f-75-69
W/bt-btif ( 3835): info:x10
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-btm  ( 3835): BTM_SwitchRole BDA: b0-c5-59-3f-75-69
,D/        ( 3835): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 2
,W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
,W/ApiaryClient( 7065): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2917826774087760176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b3e0 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x01
W/bt-btm  ( 3835): BTM: RemBdAddr: b0c5593f7569
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0041,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0041,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0044
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: b0c5593f7569  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
I/art     ( 1037): Explicit concurrent mark sweep GC freed 59201(3MB) AllocSpace objects, 10(1184KB) LOS objects, 33% free, 44MB/66MB, paused 2.498ms total 189.502ms
,D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3835): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
W/ApiaryClient( 7065): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2917826774087760176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3835): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0042,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0042,PSM: 3,peer MTU present: 0,peer MTU: 1691
,W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-btm  ( 3835): BTM_SwitchRole BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onSocketConnected: [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 837)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 838)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Outgoing connection initialized (*handshake* thread ID: 838)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 837)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 838)
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7065): Authentication error
E/BooksAccountManager( 7065): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7065): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7065): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7065): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7065): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{4a5bf2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b3e0 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
W/ApiaryClient( 7065): Error response from books API: {
W/ApiaryClient( 7065):  "error": {
W/ApiaryClient( 7065):   "errors": [
W/ApiaryClient( 7065):    {
W/ApiaryClient( 7065):     "domain": "global",
W/ApiaryClient( 7065):     "reason": "required",
W/ApiaryClient( 7065):     "message": "Login Required",
W/ApiaryClient( 7065):     "locationType": "header",
W/ApiaryClient( 7065):     "location": "Authorization"
W/ApiaryClient( 7065):    }
W/ApiaryClient( 7065):   ],
W/ApiaryClient( 7065):   "code": 401,
W/ApiaryClient( 7065):   "message": "Login Required"
W/ApiaryClient( 7065):  }
W/ApiaryClient( 7065): }
,W/ApiaryClient( 7065): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2917826774087760176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7065): Headers:
W/ApiaryClient( 7065): accept-encoding: [gzip]
W/ApiaryClient( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7065): gdata-version: 2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesRead: Read 81 bytes successfully (thread ID: 838)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Handshake succeeded with [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onHandshakeSucceeded: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 838)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7207): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7207): Entering thread (ID: 839)
,D/io.jxcore.node.OutgoingSocketThread( 7207): Server socket local port: 53817
I/io.jxcore.node.OutgoingSocketThread( 7207): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7207): onListeningForIncomingConnections: Outgoing connection is using port 53817 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 7207): 2016-01-12T12:23:53.984Z SendDataConnector.js: CLIENT connected to 53817, error: null
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:53.985Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7207): 
I/io.jxcore.node.OutgoingSocketThread( 7207): Incoming data from address: /127.0.0.1, port: 53817
D/io.jxcore.node.OutgoingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7207): Exiting thread (ID: 839)
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 841, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 840, name: Sender)
I/jxcore-log( 7207): 2016-01-12T12:23:54.013Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7207): 
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -2
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4622): Bluetooth Device Name: Nexus 5
E/BooksSync( 7065): Soft error: 
E/BooksSync( 7065): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2917826774087760176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7065): Headers:
E/BooksSync( 7065): accept-encoding: [gzip]
E/BooksSync( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7065): gdata-version: 2
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7065): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7065): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7065): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7065): {
E/BooksSync( 7065):  "error": {
E/BooksSync( 7065):   "errors": [
E/BooksSync( 7065):    {
E/BooksSync( 7065):     "domain": "global",
E/BooksSync( 7065):     "reason": "required",
E/BooksSync( 7065):     "message": "Login Required",
E/BooksSync( 7065):     "locationType": "header",
E/BooksSync( 7065):     "location": "Authorization"
E/BooksSync( 7065):    }
E/BooksSync( 7065):   ],
E/BooksSync( 7065):   "code": 401,
E/BooksSync( 7065):   "message": "Login Required"
E/BooksSync( 7065):  }
E/BooksSync( 7065): }
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7065): 	... 8 more
,E/BooksSync( 7065): Sync error
E/BooksSync( 7065): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7065): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2917826774087760176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7065): Headers:
E/BooksSync( 7065): accept-encoding: [gzip]
E/BooksSync( 7065): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7065): gdata-version: 2
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7065): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7065): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7065): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7065): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7065): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7065): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7065): {
E/BooksSync( 7065):  "error": {
E/BooksSync( 7065):   "errors": [
E/BooksSync( 7065):    {
E/BooksSync( 7065):     "domain": "global",
E/BooksSync( 7065):     "reason": "required",
E/BooksSync( 7065):     "message": "Login Required",
E/BooksSync( 7065):     "locationType": "header",
E/BooksSync( 7065):     "location": "Authorization"
E/BooksSync( 7065):    }
E/BooksSync( 7065):   ],
E/BooksSync( 7065):   "code": 401,
E/BooksSync( 7065):   "message": "Login Required"
E/BooksSync( 7065):  }
E/BooksSync( 7065): }
E/BooksSync( 7065): 
E/BooksSync( 7065): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7065): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7065): 	... 8 more
I/BooksSync( 7065): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550223, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42210
,I/jxcore-log( 7207): 2016-01-12T12:23:55.389Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:30330
,I/jxcore-log( 7207): 2016-01-12T12:23:55.674Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7207): 
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16470
,I/jxcore-log( 7207): 2016-01-12T12:23:55.841Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:55.950Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b3e0 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x00
W/bt-btm  ( 3835): BTM: RemBdAddr: b0c5593f7569
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
D/btif_config_util( 3835): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557488631510; DSPS: 18409204; Offset : -4328272042
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: b0-c5-59-3f-75-69
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b3e0 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x00
W/bt-btm  ( 3835): BTM: RemBdAddr: b0c5593f7569
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,I/jxcore-log( 7207): 2016-01-12T12:23:57.179Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:57.945Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:58.314Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:58.579Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:59.132Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:59.405Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:23:59.406Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7207): 
I/jxcore-log( 7207): oneRoundDownNow
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:59.407Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:59.408Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7207): 
,D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 7207): close
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 841
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 840
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 840, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7207): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 841, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 840, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 841, name: Receiver)
I/jxcore-log( 7207): 2016-01-12T12:23:59.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 7207): 
I/jxcore-log( 7207): ---- round done--------
I/jxcore-log( 7207): 
I/jxcore-log( 7207): startWithNextDevice
I/jxcore-log( 7207): 
I/jxcore-log( 7207): do fake peer & start
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:59.436Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:59.436Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:23:59.436Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 842)
W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-rfcomm( 3835): rfc_port_closed
W/bt-btif ( 3835): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0045
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010b0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2698): P2P-FIND-STOPPED 
D/WfdsMonitor( 1968): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=153 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/wpa_supplicant( 2698): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=154 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376d0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=155 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=157 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 3
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -3
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: Thali Test (Galaxy S5)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376d0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376d0: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionTimeout: [7C:F9:0E:37:96:AB A5-1]
,I/jxcore-log( 7207): 2016-01-12T12:24:14.459Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB A5-1] timed out
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:14.460Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB A5-1] timed out
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:14.462Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010c0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=161 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=162 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000102000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000102000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000102000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577491173639; DSPS: 19064648; Offset : -4328293233
I/jxcore-log( 7207): 2016-01-12T12:24:19.464Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:19.466Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=205228531, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{200156fc type 2 when 580342 android} when 580342
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=205228531 [*alarm*], flags=0x0
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=164 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000102000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=165 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000102000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000102000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000108000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000108000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000108000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
W/bt-btm  ( 3835): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=8 link_role=0  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): l2c_link_hci_conn_req:current link_role= 0
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000109000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000109000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=167 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 7 57000109000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-37-96-ab
W/bt-btif ( 3835): info:x10
D/        ( 3835): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 672
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0046
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3835): l2c_link_hci_conn_req:current link_role= 0
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3835): Failed to remove device: 7C:F9:0E:37:96:AB
I/BluetoothBondStateMachine( 3835): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x0046,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x0046,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onSocketConnected: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): shutdown (thread ID: 842)
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btm  ( 3835): btm_acl_created hci_handle=9 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=9 link_role=0  transport=1
W/bt-rfcomm( 3835): rfc_port_closed
W/bt-btif ( 3835): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 842)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 842)
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0047
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-34-8a-a0
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 2
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0048  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x004c,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x004c,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0048
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=168 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3835): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3835): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0049  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection initialized (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesRead: Read 63 bytes successfully (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): removeThreadFromList: Removing thread with ID 844
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Handshake thread disposed (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 S5-1]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 844)
D/io.jxcore.node.IncomingSocketThread( 7207): Entering thread (ID: 845)
,I/io.jxcore.node.IncomingSocketThread( 7207): Local host address: localhost/127.0.0.1, port: 55885
D/io.jxcore.node.IncomingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7207): Exiting thread (ID: 845)
I/jxcore-log( 7207): 2016-01-12T12:24:24.092Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7207): 
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 847, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 846, name: Sender)
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01
D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 7207): 2016-01-12T12:24:24.473Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:24.474Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:24.474Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:24.483Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 848)
,W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 7
D/LGBluetoothServiceAdapter( 3835): [BTUI] connectSocket FD=86 mFd=85
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x004a
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 7
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004b,Remote CID: 0x0048,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004b,Remote CID: 0x0048,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1
W/bt-btif ( 3835): new conn_srvc id:26, app_id:1 count:2
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onSocketConnected: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 848)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 849)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Outgoing connection initialized (*handshake* thread ID: 849)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 848)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 849)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): onBytesRead: Read 63 bytes successfully (thread ID: 849)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Handshake succeeded with [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onHandshakeSucceeded: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 849)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 7207): Entering thread (ID: 850)
D/io.jxcore.node.OutgoingSocketThread( 7207): Server socket local port: 59619
I/io.jxcore.node.OutgoingSocketThread( 7207): Now accepting connections...
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=170 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/io.jxcore.node.ConnectionHelper( 7207): onListeningForIncomingConnections: Outgoing connection is using port 59619 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 7207): 2016-01-12T12:24:24.928Z SendDataConnector.js: CLIENT connected to 59619, error: null
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:24.930Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7207): 
I/io.jxcore.node.OutgoingSocketThread( 7207): Incoming data from address: /127.0.0.1, port: 59619
D/io.jxcore.node.OutgoingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7207): Exiting thread (ID: 850)
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 852, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 851, name: Sender)
I/jxcore-log( 7207): 2016-01-12T12:24:24.953Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=171 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7207): 2016-01-12T12:24:26.058Z SendDataTCPServer.js: TCP/IP server has received 60662 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.104Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.138Z SendDataTCPServer.js: TCP/IP server has received 62642 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.145Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.150Z SendDataTCPServer.js: TCP/IP server has received 64622 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.183Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7207): 2016-01-12T12:24:26.233Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.245Z SendDataTCPServer.js: TCP/IP server has received 68582 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.259Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.283Z SendDataTCPServer.js: TCP/IP server has received 70562 bytes of data
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,I/jxcore-log( 7207): 2016-01-12T12:24:26.308Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.347Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.366Z SendDataTCPServer.js: TCP/IP server has received 74522 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.376Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.394Z SendDataTCPServer.js: TCP/IP server has received 76502 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.402Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.412Z SendDataTCPServer.js: TCP/IP server has received 78482 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.420Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.436Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.445Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.476Z SendDataTCPServer.js: TCP/IP server has received 84422 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.520Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.537Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.546Z SendDataTCPServer.js: TCP/IP server has received 86402 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.559Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.567Z SendDataTCPServer.js: TCP/IP server has received 88382 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:26.575Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.596Z SendDataTCPServer.js: TCP/IP server has received 90362 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.618Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.657Z SendDataTCPServer.js: TCP/IP server has received 92342 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:26.684Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63816
,W/bt-l2cap( 3835): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,I/jxcore-log( 7207): 2016-01-12T12:24:27.069Z SendDataTCPServer.js: TCP/IP server has received 94322 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:27.127Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:27.143Z SendDataTCPServer.js: TCP/IP server has received 96302 bytes of data,
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): btm_acl_created hci_handle=10 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=10 link_role=0  transport=1
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [34:fc:ef:11:ae:67]: 0, 0, 0
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=172 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiServerServiceExt( 1037): Connected BT device : -2
,I/jxcore-log( 7207): 2016-01-12T12:24:27.192Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 7207): 
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 3
,I/jxcore-log( 7207): 2016-01-12T12:24:27.215Z SendDataTCPServer.js: TCP/IP server has received 98282 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:27.221Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4622): Bluetooth Device Name: Nexus 5
I/jxcore-log( 7207): 2016-01-12T12:24:27.235Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:27.278Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-ae-67
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): invalid rfc slot id: 7
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 847, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7207): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 845
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 847
D/io.jxcore.node.OutgoingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 846
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 846, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7207): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 846, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 847, name: Receiver)
I/jxcore-log( 7207): 2016-01-12T12:24:27.396Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
I/jxcore-log( 7207): 2016-01-12T12:24:27.517Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
,W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x004c  Result: 0  Status: 0  BDA: 34fcef11ae67  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x01
W/bt-btm  ( 3835): BTM: RemBdAddr: 34fcef11ae67
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004c,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004c,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b770 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=173 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7207): 2016-01-12T12:24:28.194Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7207): 
,W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x004c
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x004d  Result: 0  Status: 0  BDA: 34fcef11ae67  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004d,Remote CID: 0x0042,PSM: 3,our MTU present:1,our MTU:1691
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004d,Remote CID: 0x0042,PSM: 3,peer MTU present: 0,peer MTU: 1691
,I/jxcore-log( 7207): 2016-01-12T12:24:28.654Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7207): 
,W/bt-rfcomm( 3835): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0049
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
W/bt-rfcomm( 3835): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btm  ( 3835): BTM_SwitchRole BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255 count:2
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection initialized (thread ID: 853)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 853)
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=174 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b770 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesRead: Read 66 bytes successfully (thread ID: 853)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Got valid identity from [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 853)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): removeThreadFromList: Removing thread with ID 853
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Handshake thread disposed (thread ID: 853)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 853)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 Nexus 5]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 7207): Entering thread (ID: 854)
I/jxcore-log( 7207): 2016-01-12T12:24:29.281Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7207): 
I/io.jxcore.node.IncomingSocketThread( 7207): Local host address: localhost/127.0.0.1, port: 55885
D/io.jxcore.node.IncomingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7207): Exiting thread (ID: 854)
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 856, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 855, name: Sender)
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
I/jxcore-log( 7207): 2016-01-12T12:24:29.687Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 7207): 2016-01-12T12:24:29.867Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7207): 
,D/        ( 3835): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2436
,I/jxcore-log( 7207): 2016-01-12T12:24:30.030Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.177Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.341Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.342Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7207): 
I/jxcore-log( 7207): oneRoundDownNow
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.344Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.344Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7207): 
,D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 7207): close
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 852
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 851
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 851, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7207): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 852, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 851, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 852, name: Receiver)
I/jxcore-log( 7207): 2016-01-12T12:24:30.378Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=175 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7207): ---- round done--------
I/jxcore-log( 7207): 
I/jxcore-log( 7207): startWithNextDevice
I/jxcore-log( 7207): 
I/jxcore-log( 7207): do fake peer & start
I/jxcore-log( 7207): 
I/jxcore-log( 7207): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.384Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.385Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.385Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
W/bt-rfcomm( 3835): rfc_port_closed
W/bt-btif ( 3835): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x004b
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 857)
W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 00f46f30e06c  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-btm  ( 3835): btm_acl_created hci_handle=12 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=12 link_role=0  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 16653
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 00-f4-6f-30-e0-6c
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 4
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004e,Remote CID: 0x004e,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004e,Remote CID: 0x004e,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x004e
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3835): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3835): invalid rfc slot id: 15
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 857)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Maximum number of allowed retries (0) reached, giving up... (thread ID: 857)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 857)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 7207): 2016-01-12T12:24:30.633Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.633Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.633Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7207): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): shutdown (thread ID: 857)
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7207): 2016-01-12T12:24:30.923Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.935Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.939Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.947Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.960Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.968Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.979Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.982Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:30.987Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:30.998Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.037Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.043Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.048Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.053Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.060Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.064Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.068Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.076Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.079Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.087Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.127Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.131Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.137Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.166Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.186Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.198Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.203Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.211Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.216Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.224Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.257Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.262Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.270Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.281Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.284Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.289Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.296Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.302Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=176 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7207): 2016-01-12T12:24:31.343Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.349Z SendDataTCPServer.js: TCP/IP server has received 53014 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.352Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.354Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.361Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.367Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.373Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.380Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.387Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.394Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.400Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.437Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 7c-f9-0e-37-96-ab
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b5a8 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x00
W/bt-btm  ( 3835): BTM: RemBdAddr: 7cf90e3796ab
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7207): 2016-01-12T12:24:31.491Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.507Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 7207): 
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
I/jxcore-log( 7207): 2016-01-12T12:24:31.521Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.528Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.534Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.570Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.590Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.596Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.626Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.638Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.644Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.652Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.655Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.658Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.663Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
I/jxcore-log( 7207): 2016-01-12T12:24:31.680Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.717Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:31.720Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:31.722Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7207): 
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 856, thread name: Receiver): bt socket closed, read return: -1
W/bt-btif ( 3835): invalid rfc slot id: 12
E/io.jxcore.node.IncomingSocketThread( 7207): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 854
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 856
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 855
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 855, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7207): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 855, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 856, name: Receiver)
,I/jxcore-log( 7207): 2016-01-12T12:24:31.812Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7207): 
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-rfcomm( 3835): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x004d
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
W/bt-rfcomm( 3835): RFCOMM_DisconnectInd LCID:0x4d
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=177 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1037): Connected BT device : -3
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 3
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5-1
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
W/bt-btm  ( 3835): BTM: Local device role : 0x01
W/bt-btm  ( 3835): BTM: RemBdAddr: 34fcef11ae67
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=178 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -4
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 2
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5mini-1
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -5
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: A5-1
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=179 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=1
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b218 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/btif_config_util( 3835): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=180 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376d0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2698): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1968): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=182 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -6
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=183 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: Nexus 5
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=184 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=185 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/jxcore-log( 7207): 2016-01-12T12:24:35.635Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:35.636Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C,
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=187 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=188 dispatchEvent: P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001070a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597492900922; DSPS: 19720064; Offset : -4328275092
,I/wpa_supplicant( 2698): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 2698): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 2698): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 2698): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=189 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WfdsMonitor( 1968): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=190 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=191 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=192 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
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
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms w,hat=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=80 target=com.android.i,nternal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=-28ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-28ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-29ms what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-29ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-29ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-29ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-30ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-30ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-30ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-31ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-31ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=-31ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1037): InactiveState{ when=-32ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-32ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-32ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=193 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000102000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=194 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000102000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000102000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000108000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000108000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=195 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000108000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000109000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000109000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=196 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 58000109000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010b000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=197 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010b000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010b000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again,
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=198 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 7207): 2016-01-12T12:24:40.641Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:40.642Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:40.642Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:40.643Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 859)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7207): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 00f46f30e06c  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=199 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=200 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=201 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=202 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3835): btm_acl_created hci_handle=14 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=14 link_role=0  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): l2c_link_hci_conn_req:current link_role= 0
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3835): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
D/WifiServerServiceExt( 1037): Connected BT device : -5
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5mini-1
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 16653
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 00-f4-6f-30-e0-6c
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x004f,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x004f,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x004f
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3835): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3835): invalid rfc slot id: 16
W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 00f46f30e06c  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 7
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0041,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0041,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3835): btm_acl_created hci_handle=13 link_role=1  transport=1
W/bt-btm  ( 3835): btm_acl_created hci_handle=13 link_role=0  transport=1
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3835): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
W/bt-sdp  ( 3835): process_service_search_attr_rsp
W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0040
D/WifiServerServiceExt( 1037): Connected BT device : -4
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3835): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3835): invalid rfc slot id: 17
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 859)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Maximum number of allowed retries (0) reached, giving up... (thread ID: 859)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 859)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 7207): 2016-01-12T12:24:43.233Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:43.233Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:43.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7207): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): shutdown (thread ID: 859)
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 2
I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: XT1072
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 44-80-eb-7b-5a-05
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: 4480eb7b5a05  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x004d,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x004d,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0041  Result: 0  Status: 0  BDA: 4480eb7b5a05  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x004e,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x004e,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection initialized (thread ID: 861)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 861)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesRead: Read 65 bytes successfully (thread ID: 861)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Got valid identity from [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): onBytesWritten: 63 bytes successfully written (thread ID: 861)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): removeThreadFromList: Removing thread with ID 861
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Handshake thread disposed (thread ID: 861)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnected: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 XT1072]
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7207): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 XT1072], created successfully
D/io.jxcore.node.ConnectionHelper( 7207): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 861)
D/io.jxcore.node.IncomingSocketThread( 7207): Entering thread (ID: 862)
I/io.jxcore.node.IncomingSocketThread( 7207): Local host address: localhost/127.0.0.1, port: 55885
D/io.jxcore.node.IncomingSocketThread( 7207): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7207): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7207): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7207): Exiting thread (ID: 862)
,I/jxcore-log( 7207): 2016-01-12T12:24:43.528Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7207): 
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 864, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7207): Entering thread (ID: 863, name: Sender)
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=203 dispatchEvent: P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 7 120001080a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=204 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001090a436f72646f7661703270c00c000c01
I/jxcore-log( 7207): 2016-01-12T12:24:44.927Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:44.940Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:44.955Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:44.968Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:44.976Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:44.982Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:44.992Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:44.998Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.007Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.016Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.030Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.066Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.074Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.082Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.100Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.109Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.116Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.126Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.135Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.145Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.153Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.186Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.219Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.232Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.243Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.262Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.278Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.286Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.292Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.302Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.337Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.370Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.383Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.387Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.389Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=205 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7207): 2016-01-12T12:24:45.399Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.406Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.436Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.443Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.450Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.457Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.471Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.486Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.521Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.563Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.574Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.582Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.589Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.592Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.598Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.604Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.618Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.657Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.671Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.686Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.701Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.709Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.715Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.721Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.728Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.738Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7207): 2016-01-12T12:24:45.776Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 7207): 
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
I/jxcore-log( 7207): 2016-01-12T12:24:45.785Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 7207): 
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376d0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376d0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/jxcore-log( 7207): 2016-01-12T12:24:45.821Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.828Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.834Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.840Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.846Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.886Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.893Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.895Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.899Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.936Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.972Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.981Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.984Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:45.988Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:24:45.995Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7207): 
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3835): invalid rfc slot id: 14
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 864, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7207): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 862
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 864
D/io.jxcore.node.IncomingSocketThread( 7207): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7207): doStop: Thread ID: 863
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7207): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7207): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7207): Either failed to read from the output stream or write to the input stream (thread ID: 863, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7207): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7207): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 864, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7207): Exiting thread (ID: 863, name: Sender)
W/bt-rfcomm( 3835): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0041
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-rfcomm( 3835): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 7207): 2016-01-12T12:24:46.049Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7207): 
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b050 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=207 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376d0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=208 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -5
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5mini-1
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010c000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010c000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=209 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010c000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
I/jxcore-log( 7207): 2016-01-12T12:24:48.236Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:48.237Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=210 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/[SystemUI]LGPowerUI( 1459): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1459): On Skip Timer : true
,D/btif_config_util( 3835): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -6
I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: XT1072
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=211 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01
D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 7207): 2016-01-12T12:24:53.241Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:53.242Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:53.243Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:24:53.243Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
,I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 865)
,W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 00f46f30e06c  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=212 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617494755029; DSPS: 20375485; Offset : -4328282557
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=213 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010d0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=214 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010d0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=215 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=216 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=217 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
,I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=219 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=220 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=221 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010e0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7207): timeout now
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): weAreDoneNow, resultArray.length: 4
I/jxcore-log( 7207): 
I/jxcore-log( 7207): sendReportNow
I/jxcore-log( 7207): 
I/jxcore-log( 7207): done, now sending data to server
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:25:08.083Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7207): 
D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 7207): 2016-01-12T12:25:08.084Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionTimeout: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 7207): 2016-01-12T12:25:08.275Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:25:08.276Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:08.277Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7207): 
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=222 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376d0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376d0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7207): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service request added successfully
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=224 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376d0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2698): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1968): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=225 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service discovery started successfully
,I/wpa_supplicant( 2698): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=226 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
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
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=227 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)],
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=228 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010f0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=229 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 1200010f0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=230 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=231 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01
I/jxcore-log( 7207): 2016-01-12T12:25:13.277Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:13.278Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637496897053; DSPS: 21030915; Offset : -4328276815
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=232 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=233 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1968): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
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
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1968): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galax,y S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=234 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000102000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=235 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000108000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=236 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000109000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=237 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7207): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 7207): 2016-01-12T12:25:18.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:18.283Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:18.284Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:18.284Z SendDataConnector.js: do connect now
I/jxcore-log( 7207): 
,I/io.jxcore.node.ConnectionHelper( 7207): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 7207): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 7207): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 7207): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7207): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7207): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 867)
,W/LGMDMUISystemServiceAdapter( 7207): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7207): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3835): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=238 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 1200010e0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=239 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=240 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=241 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=242 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=243 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1968): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=244 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=245 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 1
,W/bt-sdp  ( 3835): SDP - Rcvd conn cnf with error: 0x22  CID 0x43
E/bt-btif ( 3835): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
W/bt-l2cap( 3835): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 00f46f30e06c  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,W/bt-btif ( 3835): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 865)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Maximum number of allowed retries (0) reached, giving up... (thread ID: 865)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 865)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): shutdown (thread ID: 865)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 7207): 2016-01-12T12:25:23.589Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): 2016-01-12T12:25:23.589Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:23.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7207): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1968): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=246 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=205228531, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=205228531 [*alarm*], flags=0x0
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 00-f4-6f-30-e0-6c
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=16 link_role=1  transport=1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=16 link_role=1  transport=1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3835): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): l2c_link_hci_conn_req:current link_role= 0
W/bt-btif ( 3835): info:x10
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,D/WifiServerServiceExt( 1037): Connected BT device : -5
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5mini-1
W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 16653
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 00-f4-6f-30-e0-6c
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x004a,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x004a,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-sdp  ( 3835): process_service_search_attr_rsp
,W/bt-l2cap( 3835): L2CA_DisconnectReq()  CID: 0x0044
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3835): btm_acl_created hci_handle=15 link_role=1  transport=1
,W/bt-btm  ( 3835): btm_acl_created hci_handle=15 link_role=0  transport=1
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3835): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3835): invalid rfc slot id: 20
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): shutdown (thread ID: 867)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 867)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Maximum number of allowed retries (0) reached, giving up... (thread ID: 867)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7207): Exiting thread (thread ID: 867)
,W/bt-btm  ( 3835): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3835): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3835): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3835): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
W/bt-btif ( 3835): info:x10
W/bt-btm  ( 3835): BTM_SwitchRole BDA: 00-f4-6f-30-e0-6c
W/bt-btm  ( 3835): Requested New Role: 0
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3835): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3835): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3835): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL connected => AclLinkCount = 2
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 00-f4-6f-30-e0-6c
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b938 rs_disc_pending=1
,W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0045  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0045
,W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3835): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3835): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3835): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3835): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3835): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothRemoteDevices( 3835): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3835): Failed to remove device: 08:EC:A9:50:75:41
,W/bt-btm  ( 3835): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-l2cap( 3835): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3835): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3835): L2CA_ErtmConnectRsp()  CID: 0x0046  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 24
I/BluetoothBondStateMachine( 3835): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3835): StableState(): Entering Off State
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3835): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0043,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3835): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3835): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0043,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/jxcore-log( 7207): 2016-01-12T12:25:28.602Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:28.603Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 7207): 
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255
W/bt-btif ( 3835): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3835): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3835): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Incoming connection initialized (thread ID: 869)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Entering thread (ID: 869)
,W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3835): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): removeThreadFromList: Removing thread with ID 869
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Handshake failed (thread ID: 869)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7207): Exiting thread (ID: 869)
W/bt-rfcomm( 3835): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-l2cap( 3835): L2CA_DisconnectRsp()  CID: 0x0046
W/bt-l2cap( 3835): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-rfcomm( 3835): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btm  ( 3835): btm_acl_role_changed: BDA: 00-f4-6f-30-e0-6c
,W/bt-btm  ( 3835): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3835): tBTM_SEC_DEV:0xa038b938 rs_disc_pending=0
W/bt-btif ( 3835): bta_dm_check_av:0
,W/bt-btif ( 3835): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7207): teardown,
I/jxcore-log( 7207): 
,I/jxcore-log( 7207): testSendData stopped
I/jxcore-log( 7207): 
I/io.jxcore.node.ConnectionHelper( 7207): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7207): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7207): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7207): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7207): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2698): P2P-FIND-STOPPED 
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=247 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1968): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7207): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7207): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7207): setState: NOT_STARTED
I/jxcore-log( 7207): StopBroadcasting went ok
I/jxcore-log( 7207): 
I/jxcore-log( 7207): ****TEST TOOK:  ms ****
I/jxcore-log( 7207): 
I/jxcore-log( 7207): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7207): 
I/jxcore-log( 7207): 2016-01-12T12:25:30.247Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7207): 
,I/io.jxcore.node.ConnectionHelper( 7207): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7207): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7207): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7207): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7207): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7207): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
E/bt-btm  ( 3835): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3835): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -6
,I/BluetoothMapService( 3835): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3835): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3835): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3835): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3835): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7279): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4622): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4622): Bluetooth Device Name: S5mini-1
,D/AndroidRuntime( 8035): 
D/AndroidRuntime( 8035): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8035): CheckJNI is OFF
,D/AndroidRuntime( 8035): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 7207:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1037): Skipping PackageSetting{d785c42 com.example.hello/10319} due to missing metadata
,I/WindowState( 1037): WIN DEATH: Window{87b13e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{87b13e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2a74a45d u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{bfb0185 7207:com.test.thalitest/u0a311}, curProc for 7207: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2a74a45d u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{2a74a45d u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2090): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{1908ca5a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{3201c48b co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,E/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,D/LIA_MrGDBLogger_PackageInfoDetector( 3777): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1840): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4565): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4565): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4565): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4565): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4565): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4565): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4565): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4565): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4565): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4565): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4565): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4565): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8077 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/art     ( 4622): Explicit concurrent mark sweep GC freed 45217(2MB) AllocSpace objects, 7(112KB) LOS objects, 34% free, 30MB/46MB, paused 596us total 101.074ms
I/[LGHome]EVENT( 2090): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1926): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3777): handleMessage: what(1000) actionID(0x1000003)
,I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2090): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2090): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2090): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1926): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 3777): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3777): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2090): , create_time: 1430558575574
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2090): , create_time: 1430558575600
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2090): , create_time: 1452175675684
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/art     ( 1037): Explicit concurrent mark sweep GC freed 45917(2MB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 2.246ms total 169.105ms
I/art     ( 1037): WaitForGcToComplete blocked for 161.983ms for cause Explicit
,D/SplitUIManager( 1892): split_name #11 / not available #0
D/SplitUIService( 1892): removed split : 
,D/WallpaperManager( 2090): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@244d8989,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/AppUp4:PreloadHelper( 7464): added Exclude : com.test.thalitest
,I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8098 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/SplitUIManager( 1892): split_name #11 / not available #0
I/SplitUIService( 1892): split app #11
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/LockScreenSettings( 8077): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/administrator( 1037): Handling package changes for user 0
,W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          displayName: Google Play Music
I/ThermalEngine(  324): Thermal-Server: Thermal received msg from  override
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [-] updateMediaPlayerInfo
I/Thermal-Lib( 3144): Thermal-Lib-Client: Client request sent
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
I/[LGHome]EVENT( 2090): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 8098): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8098): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8098): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8098): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8098): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
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
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): handleShortcutListChanged...
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
,D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
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
I/ActivityManager( 1037): Killing 6302:com.android.vending/u0a44 (adj 15): empty #17
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2090): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1459): handleShortcutListChanged...
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6302/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2617): onStartCommand(). Type : 8
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{247d9305 u0 com.lge.launcher2/.Launcher t3} time:652221
D/[Concierge]Service( 2617): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]WidgetView( 2090): change position of spinner
D/[Concierge]Service( 2617): Update widget ID : 11
I/art     ( 1037): Explicit concurrent mark sweep GC freed 10225(525KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/67MB, paused 5.738ms total 267.776ms
I/[Concierge]WidgetView( 2090): initWebView(). Time : 1452601531556
D/[Concierge]Service( 2617): onStartCommand(). Type : 0
I/SystemConfig( 8098): BUILD Country: EU
I/SystemConfig( 8098): BUILD Operator: OPEN
,I/[Concierge]WebView( 2090): Return exist ConciergeWebView. Reuse : 450458412
D/[Concierge]WidgetView( 2090): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2090): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@179f8d23
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2090): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2090): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2090): Widget kill message received. Destory myself. My : 1452600907188, New one : 1452601531556
D/[Concierge]WidgetView( 2090): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2090): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1037): Killing 7316:com.lge.sync/1000 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
D/AndroidRuntime( 8035): Shutting down VM
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2090): Timeline: Activity_idle id: android.os.BinderProxy@76f2525 time:652327
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7316/cgroup.procs: No such file or directory
,I/SystemConfig( 8098): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 8098): existFile = false
I/SystemConfig( 8098): canReadFile = false
I/SystemConfig( 8098): systemFeature RCS result false
D/SystemConfig( 8098): refreshRcsSupport() :false
I/PackageChangeReceiver( 7496): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2165): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8122 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 8122): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/chromium( 2090): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/GBoardtInterface( 2090): onReloaded()
,I/GBoardWebViewClient( 2090): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3777): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3777): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/AppConfig( 8122): Total System Memory = 2995761152
D/ActionManagerService( 1926): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3777): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3777): onEvent() : ACTION_BOARD_ENABLED
D/SystemHelper( 8122): region [EU], country [EU], operator [OPEN], sub-operator []
,D/ActionManagerService( 1926): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3777): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3777): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3777): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3777): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3777): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/ActivityManager( 1037): Killing 7524:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2047): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7524/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 7575:com.android.chrome/u0a57 (adj 15): empty #17
D/LIA_Service_LIAService( 2047): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,W/libprocessgroup( 1037): failed to open /acct/uid_10057/pid_7575/cgroup.procs: No such file or directory
D/PostponalbeReceiver( 6727): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/CoreEventReceiver( 7832): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7279): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7279): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7279): replacing : false
,D/HideNavigationAppsReceiver( 7279): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7279): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7279): replacing : false
I/UpdateIcingCorporaServi( 4622): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/ActivityManager( 1037): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8147 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SQLiteLog( 4622): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/art     (  346): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 13.879ms
--------- beginning of crash
E/AndroidRuntime( 4622): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4622): Process: com.google.android.googlequicksearchbox:search, PID: 4622
E/AndroidRuntime( 4622): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4622): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4622): 	at csx.d(PG:186)
E/AndroidRuntime( 4622): 	at cun.g(PG:594)
E/AndroidRuntime( 4622): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4622): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 4622): 	at android.content.ContentResolver.update(ContentResolver.java:1349)
E/AndroidRuntime( 4622): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4622): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4622): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4622): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4622): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4622): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4565): (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 4565): Error inserting f004=13 f005=8147 f002=1452601531984 f003=com.google.android.apps.docs f006=10061
E/SQLiteDatabase( 4565): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 4565): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 4565): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 4565): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 4565): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 4565): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
E/SQLiteDatabase( 4565): 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
E/SQLiteDatabase( 4565): 	at com.lge.mlt.MltMonitor,Service$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
E/SQLiteDatabase( 4565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4565): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4565): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,I/art     (  346): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 8.867ms
I/Process ( 4622): Sending signal. PID: 4622 SIG: 9
E/DropBoxManagerService( 1037): Can't write: system_app_crash
E/DropBoxManagerService( 1037): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1037): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1037): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1037): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1037): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1037): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1037): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1037): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1037): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1037): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1037): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1037): 	... 5 more
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.911ms

```
