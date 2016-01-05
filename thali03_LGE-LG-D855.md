#### Test 54970261aa56788_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 277778381876; DSPS: 9243014; Offset : -4309573572
,D/AndroidRuntime( 7073): 
D/AndroidRuntime( 7073): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7073): CheckJNI is OFF
D/AndroidRuntime( 7073): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1970): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{6083095 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{6083095 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7092 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7073): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1874): Display #0 changed.
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{35a325b4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{292c15dd co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7092): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7092): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7092): Loading: webviewchromium
,I/LibraryLoader( 7092): Time to load native libraries: 4 ms (timestamps 3291-3295)
I/LibraryLoader( 7092): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7092): Binding Chromium to main looper Looper (main, tid 1) {32d54264}
,I/LibraryLoader( 7092): Expected native library version number "",actual native library version number ""
I/chromium( 7092): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7092): Initializing chromium process, renderers=0
,W/art     ( 7092): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  318): registerClient() client 0xb558a2e0, uid 10311
,W/chromium( 7092): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7092): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7092): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7092): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7092): Build Date: 12/12/14 금
I/Adreno-EGL( 7092): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7092): Remote Branch: 
I/Adreno-EGL( 7092): Local Patches: 
I/Adreno-EGL( 7092): Reconstruct Branch: 
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 26143(1153KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.052ms total 131.259ms
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@251fe002:true
W/chromium( 7092): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7092): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7092): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7092): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{388845aa u0 com.test.thalitest/.MainActivity t4}
,D/SystemWebViewEngine( 7092): CordovaWebView is running on device made by: LGE
W/art     ( 7092): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7092): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7092): Render dirty regions requested: true
,I/OpenGLRenderer( 7092): Initialized EGL, version 1.4
D/OpenGLRenderer( 7092): Enabling debug mode 0
,D/Atlas   ( 7092): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{1617ceb9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7092): LgDataFeature() Constructor: none
D/LgDataFeature( 7092): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1470): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4c3c69c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +723ms (total +798ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{388845aa u0 com.test.thalitest/.MainActivity t4} time:293803
,I/Timeline( 7092): Timeline: Activity_idle id: android.os.BinderProxy@a400c94 time:293809
I/chromium( 7092): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7092): 
,D/JsMessageQueue( 7092): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7092): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435073280
D/JX-Cordova( 7092): jxcore cordova android initializing
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7092): Initializing JXcore engine
W/jxcore-log( 7092): JXcore engine is ready
W/jxcore-log( 7092): Starting JXcore engine
W/.test.thalitest( 7092): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8325]" dev="sockfs" ino=8325 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7092): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7092): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9621]" dev="sockfs" ino=9621 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7092): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7092): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33638]" dev="sockfs" ino=33638 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7092): Platform android
W/jxcore-log( 7092): 
W/jxcore-log( 7092): Process ARCH arm
W/jxcore-log( 7092): 
I/jxcore-log( 7092): JXcore Cordova bridge is ready!
I/jxcore-log( 7092): 
W/jxcore-log( 7092): JXcore engine is started
,I/jxcore-log( 7092): Toggling radios to true
I/jxcore-log( 7092): 
,D/BluetoothAdapter( 7092): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=7092, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=7092, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1036): disconnect pid=7092, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1036): [296,722,187 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1036): reconnect pid=7092, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7092): Radios toggled
I/jxcore-log( 7092): 
,I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1036): InitialState.processMessage what=4
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,D/DhcpStateMachine( 1036): RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7180 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/CommandListener(  314): Clearing all IP addresses on wlan0
V/NativeCrypto( 2132): Read error: ssl=0xaa75fc00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2132): SSL shutdown failed: ssl=0xaa75fc00: I/O error during system call, Broken pipe
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): Dns fail occured do internet check.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/DSQN    ( 1036): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1036): try Internet connection check
D/WifiHS20( 1036): hidePasspointNotification off =false
,V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1036): [296,898,643 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296900
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296900
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  314): Clearing all IP addresses on wlan0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1036): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1036): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1036): InternetcheckProgress is not set don't send DS quality intent
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296943  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296943  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296950  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1,.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20( 1036): hidePasspointNotification off =false
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1036): Removing idletimer
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToPr,ovisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
W/ResourcesManager( 7180): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7180): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7180): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7180): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7180): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7180): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7180): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7180): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7180): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7180): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7180): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7180): [AUTORUN] setTetherStatus() : status=false
,D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-182ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7220 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6673:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6673/cgroup.procs: No such file or directory
,I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7220): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7180): LgDataFeature() Constructor: none
D/LgDataFeature( 7180): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7244 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1036): Killing 6125:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6125/cgroup.procs: No such file or directory
,W/ResourcesManager( 7244): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7244): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 297779498640; DSPS: 9898410; Offset : -4309554919
D/QRemote ( 7244): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7244): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7244): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7244): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7244): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7244): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7244): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7244): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7220): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7244): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7220): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7220): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7244): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7244): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/DSQN    ( 1036): EVENT_INTERNET_CHECK_ENABLE received
D/LgDataFeature( 7244): LgDataFeature() Constructor: none
D/LgDataFeature( 7244): LgDataFeature() Constructor Done, null
,V/SoundPool( 7244): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7244): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7244): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7244): doLoad: loading sample sampleID=1
V/SoundPool( 7244): Start decode
V/MediaPlayer[Native]( 7244): decode(31, 10857164, 17813)
V/MediaPlayerService(  318): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474b80, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
I/QRemote ( 7244): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,D/QRemote ( 7244): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6846): QS Service created
E/QRemote ( 7244): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7244): Create singleton instance
V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
V/AwesomePlayer(  318): prepareAsync_l() 
V/MediaPlayerService(  318): wait for prepare
V/AwesomePlayer(  318): onPrepareAsyncEvent() 
V/AwesomePlayer(  318): initAudioDecoder() 
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AwesomePlayer(  318): getUseOffload() = 0 
V/OMXCodec(  318): OMXCodec::Create
V/OMXCodec(  318): findMatchingCodecs()
V/OMXCodec(  318): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  318): matchingCodecs.size()=1
V/OMXCodec(  318): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  318): LG Codec Adapter start
V/OMXCodec(  318): OMXCodec Createtor
V/OMXCodec(  318): setComponentRole
V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
V/LGCodecOSAL(  318): Not support LGCodec
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  318): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  318): Could not offload audio decode, try pcm offload
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  318): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  318): init()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  318): allocateBuffers
V/OMXCodec(  318): allocateBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.d,ecoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb5474b80, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb5474b80, 1, 0, 0)
V/AudioCache(  318): prepared
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): start
V/AwesomePlayer(  318): play_l() 
V/AwesomePlayer(  318): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  318): createAudioPlayer_l
V/AwesomePlayer(  318): seekAudioIfNecessary_l() 
V/AwesomePlayer(  318): startAudioPlayer_l() 
D/AudioPlayer(  318): start of Playback, useOffload 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb57c1240 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb5474b80, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac300000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac301000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac302000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac303000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac304000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac305000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac306000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac307000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac308000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac309000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30a000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30b000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30c000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30d000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30e000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac30f000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac310000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac311000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac312000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac313000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac314000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac315000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac316000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac317000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac318000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac319000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31a000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31b000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31c000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31d000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31e000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac31f000, 0xb040b000, 4096)
,V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac320000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac321000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac322000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac323000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac324000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac325000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac326000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac327000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac328000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac329000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32a000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32b000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32c000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32d000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32e000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac32f000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac330000, 0xb040b000, 4096)
V/AudioCache(  318): write(0xb040b000, 4096)
V/AudioCache(  318): memcpy(0xac331000, 0xb040b000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb040b000, 280)
V/AudioCache(  318): memcpy(0xac332000, 0xb040b000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb5474b80, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb5474b80, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  318): Pause Playback at 1068125
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474b80, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb57c1240 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 7244): close(31)
V/SoundPool( 7244): pointer = 0x9ff31000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6846): Service initServices...
D/UEI.SmartControl( 6846): QS start get config
,D/QRemote ( 7244): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5687
I/UEI.SmartControl( 6846): Supports setup maps: true
,D/UEI.SmartControl( 6846): QS start statue = true Error code = 0
I/UEI.SmartControl( 6846): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6846): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6846): ### init IR Blaster...
D/serial_port( 6846): Configuring serial port
E/UEI.SmartControl( 6846): UEIBLaster setting for 616
I/UEI.SmartControl( 6846): Setting serial record hearder size = 2
I/UEI.SmartControl( 6846): configuring settings for MAXQ616
I/UEI.SmartControl( 6846): Get version...
D/UEI.SmartControl( 6846): serial port data available: 21
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2d178762 type 2 when 239841 android} when 239841
,D/UEI.SmartControl( 6846): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6846): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6846): QS saving settings...
D/UEI.SmartControl( 6846): IR Blaster version: 25672567
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/UEI.SmartControl( 6846): serial port data available: 4
I/UEI.SmartControl( 6846): Device manager: loading config....
,W/ContextImpl( 6846): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 6846): ----------- loading internal config...
E/UEI.SmartControl( 6846): Services init done
D/UEI.SmartControl( 6846): QS Service init finished
D/UEI.SmartControl( 6846): QS Service version name: 2.1.91
D/UEI.SmartControl( 6846): QS Service version code: 201091
D/UEI.SmartControl( 6846): Service requested: Control
E/UEI.SmartControl( 6846): Loading SETTINGS...
D/UEI.SmartControl( 6846): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6846): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 7244): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6846): Internal service binding...
I/UEI.SmartControl( 6846): ------ IControl API: 11
D/UEI.SmartControl( 6846): File observer start...
E/UEI.SmartControl( 6846): IR Port is disabled: false
D/UEI.SmartControl( 6846): Starting file observer...
I/UEI.SmartControl( 6846): Registering callback...
I/UEI.SmartControl( 6846): ------ IControl API: 19
,I/UEI.SmartControl( 6846): Registering Services Ready callback...
I/UEI.SmartControl( 6846): Notify client services are ready...
I/QRemote ( 7244): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7244): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7244): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7244): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7244): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6846): ------ IControl API: 8
D/QRemote ( 7244): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7244): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7244): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7244): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7244): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7244): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7244): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
I/UEI.SmartControl( 6846): Notify AllClients services are ready: 0
I/QRemote ( 7244): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7244): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7244): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6846): -----service ready thread exits
V/QRemote ( 7244): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7244): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 7244): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452019473362]
D/QRemote ( 7244): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6146:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7244): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
D/QRemote ( 7244): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6146/cgroup.procs: No such file or directory
,V/QRemote ( 7244): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7244): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7244): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2681): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=299030  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=299052  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2681): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=299143  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=299143  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299143
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299143
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299144
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299144
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299144
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=299144  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 2681): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=299151 , SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7180): [AUTORUN] sys.usb.config = ptp_only,adb
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7180): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7180): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=299153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=299153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=299153
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=299153
D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATED
D/UsbSettingsControl( 7180): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7180): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7180): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
D/UsbSettingsControl( 7180): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1036): Got NetworkAgent Messenger
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1036): NetworkAgent connected
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299202  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299202  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299203  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299207  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299211  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299213  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cfed359 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cfed359 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2681): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): ignoring duplicate network state non-change
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
,V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
,D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
,D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/dsqn    ( 7306): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6846 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7306): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6846 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
E/DSQN    ( 7306): DSQN ssw
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7244): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7244): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7244): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7244): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7220): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7220): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7180): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7180): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
,D/QRemote ( 7244): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7244): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7244): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7244): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7244): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7312): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6846 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 18:44:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452019474366], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452019474342]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
W/dhcpcd  ( 7312): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6846 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Validated
D/ConnectivityService( 1036): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/dhcpcd  ( 7312): version 5.5.6 starting
E/dhcpcd  ( 7312): get_duid: m
D/dhcpcd  ( 7312): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7312): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7312): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7312): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7312): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7312): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7312): wlan0: sending REQUEST (xid 0x81793924), next in 4.88 seconds
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5452): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5452): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7340 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7340): onCreate
W/AppUp4:DB( 7340):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7340):  setFingerPrint start
I/AppUp4:DB( 7340):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7340):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7340):  SDK version = 21
I/AppUp4:DB( 7340):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7340): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7340): onReceive
,D/LgDataFeature( 7340): LgDataFeature() Constructor: none
D/LgDataFeature( 7340): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@28c7982
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7340): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7340): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7340): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7340): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6571:com.android.defcontainer/u0a4 (adj 15): empty #17
E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524295
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6571/cgroup.procs: No such file or directory
,D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3422): DownloadService onCreate
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3422): in removeSpuriousFiles
I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3422): DownloadService onStartCommand
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@2e0564f4 on behalf of 3422
D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@5c6841d on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3422): in trimDatabase
D/eas_req ( 6698): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): processing inserted download 1
,V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3d354692 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
,V/DownloadManager( 3422): processing inserted download 21
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7375 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 6698): JNI_OnLoad()
I/HubEmail( 6698): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6698): registerNatives()
I/HubEmail( 6698): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6698): registerNativeMethods()
I/HubEmail( 6698): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6698): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,V/DownloadManager( 3422): DownloadService onDestroy
I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 20.416ms
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 18.139ms
,I/LgeMiscReceiver( 3356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3356): networkInfo.isConnected() = false
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 351us total 15.889ms
,I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7398 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 7312): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7312): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7312): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7312): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7312): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7312): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7312): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7312): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7312): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7425 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6725:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6725/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7455 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6751:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6751/cgroup.procs: No such file or directory
,I/art     ( 7455): Almond Protected OAT
,V/FormManager( 7375): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7375): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1036): Killing 6775:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6775/cgroup.procs: No such file or directory
,D/WeatherApplication( 7455): removeAccount
D/WeatherApplication( 7455): Account.length = 0
E/WeatherApplication( 7455): OPERATOR:OPEN
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{20c59f09 type 2 when 301275 com.google.android.gms} when 301275
,D/WeatherAncestor( 7455): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:36
,D/Weather.Utils( 7455): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7455): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7455): 2 : This is isUpdating : false
D/WeatherAncestor( 7455): connectivity changed - connection : true
D/WeatherService( 7455): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7455): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7455): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7455): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7455): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7455): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:36
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7477 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6825:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6825/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7477): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7477): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7477): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7477): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7477): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7477): Loading: webviewchromium
I/LibraryLoader( 7477): Time to load native libraries: 4 ms (timestamps 1876-1880)
,I/LibraryLoader( 7477): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7477): Binding Chromium to main looper Looper (main, tid 1) {29dffcf5}
I/LibraryLoader( 7477): Expected native library version number "",actual native library version number ""
I/chromium( 7477): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7477): Initializing chromium process, renderers=0
W/art     ( 7477): Attempt to remove local handle scope entry from IRT, ignoring
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/chromium( 7477): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7477): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7477): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  318): registerClient() client 0xb558adc0, uid 10093
W/AudioManagerAndroid( 7477): Requires BLUETOOTH permission
I/Adreno-EGL( 7477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7477): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7477): Build Date: 12/12/14 금
I/Adreno-EGL( 7477): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7477): Remote Branch: 
I/Adreno-EGL( 7477): Local Patches: 
I/Adreno-EGL( 7477): Reconstruct Branch: 
,I/NSApplication( 7477): Starting up...
,I/ActivityManager( 1036): Killing 6866:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6866/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7340): onReceive
,D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@28c7982
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3422): DownloadService onCreate
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 3356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3356): networkInfo.isConnected() = false
D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@78ddc60 on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@2cc4519 on behalf of 3422
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7455): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:37
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3422): DownloadService onStartCommand
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/Weather.Utils( 7455): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7455): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7455): 2 : This is isUpdating : false
D/WeatherAncestor( 7455): connectivity changed - connection : true
D/WeatherService( 7455): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8d620d0
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@21645e8c on behalf of 3422
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
V/DownloadManager( 3422): processing inserted download 1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
V/DownloadManager( 3422): processing inserted download 4
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
V/DownloadManager( 3422): processing inserted download 7
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/DownloadManager( 3422): processing inserted download 8
D/ForecastDataCache( 7455): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7455): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7455): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7455): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7455): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:37
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5452): type=WIFI subType= reason=null isConnected=true
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/DownloadManager( 3422): DownloadService onDestroy
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7340): onReceive
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/FormManager( 7375): There are no updated forms. The schedule will be deleted.
D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@28c7982
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/FormManager( 7375): Alarm would be updated, because LastCheckTime has been updated.
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3422): DownloadService onCreate
D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3422): in removeSpuriousFiles
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
I/LgeMiscReceiver( 3356): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3356): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3356): networkInfo.isConnected() = true
D/PhoneState( 3356): setPdpRejectCasuse : false
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WeatherAncestor( 7455): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:37
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
V/DownloadManager( 3422): DownloadService onStartCommand
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/Weather.Utils( 7455): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7455): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7455): 2 : This is isUpdating : false
D/WeatherAncestor( 7455): connectivity changed - connection : true
D/WeatherService( 7455): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@8d620d0
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/ForecastDataCache( 7455): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7455): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7455): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7455): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7455): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:44:37
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@383ed778 on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@37387e51 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3d30a6b6 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 21
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3422): DownloadService onDestroy
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7375): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7375): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1036): Explicit concurrent mark sweep GC freed 84867(3MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.802ms total 79.531ms
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/GCM     ( 2132): Connected
W/Kids    ( 2367): [AccountUtils] Account not ready
W/Kids    ( 2367): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2367): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2367): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2367): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/GCM     ( 2132): Message class com.google.f.a.a.p
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6846): Internal timer expired: 4
D/UEI.SmartControl( 6846): unbind internal service
,D/serial_port( 6846): close(fd = 24)
,I/UEI.SmartControl( 6846): Serial port is closed.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7092): Test app app.js loaded
I/jxcore-log( 7092): 
,I/chromium( 7092): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7092): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7092): 
I/chromium( 7092): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV4    ( 7477): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{5a86b32 type 2 when 306932 android} when 306932
,V/QRemote ( 7244): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 7244): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5687
,I/BooksSync( 6983): Starting books sync
,D/BooksSync( 6983): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
,D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9051265152096237839&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9051265152096237839&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9051265152096237839&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
E/BooksSync( 6983): Soft error: 
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9051265152096237839&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
,E/BooksSync( 6983): Sync error
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9051265152096237839&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
I/BooksSync( 6983): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 306932, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 317781455821; DSPS: 10553834; Offset : -4309551072
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,I/ActivityManager( 1036): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7598 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7598): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7598): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@d0a3f7
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
I/ActivityManager( 1036): Killing 6895:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6895/cgroup.procs: No such file or directory
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{aa00bbf type 2 when 337021 android} when 337021
,I/jxcore-log( 7092): TAP version 13
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # multiplex can send data
I/jxcore-log( 7092): 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 337782503730; DSPS: 11209229; Offset : -4309571304
,E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 1 String should be length:200
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # basic
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 2 sane
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # another
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 3 sane
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 357784180806; DSPS: 11864644; Offset : -4309572591
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 4 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 5 null
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 6 (unnamed assert)
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 7 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 8 should not throw
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 9 (unnamed assert)
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 10 (unnamed assert)
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 11 should not throw
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 12 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 13 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 6249): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6249): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6249): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6249): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6249): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
I/jxcore-log( 7092): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7092): 
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 14 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # failed to get mobile documents path
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 377785902100; DSPS: 12520060; Offset : -4309560437
,I/jxcore-log( 7092): ok 15 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,I/jxcore-log( 7092): ok 16 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 17 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 18 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #init should register the networkChanged event
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 19 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #startBroadcasting should throw on null device name
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 397787911675; DSPS: 13175486; Offset : -4309564970
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 20 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 21 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 22 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 417789847762; DSPS: 13830909; Offset : -4309551621
,I/jxcore-log( 7092): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 23 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #startBroadcasting should throw on negative port
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3787): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 7092): ok 24 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #startBroadcasting should throw on too large port
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 437791851088; DSPS: 14486335; Offset : -4309562507
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 25 should throw
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
I/jxcore-log( 7092): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 26 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 27 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 28 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 457793462121; DSPS: 15141748; Offset : -4309569011
,I/jxcore-log( 7092): ok 29 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 30 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 31 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 32 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 33 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 34 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 35 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 477795172166; DSPS: 15797164; Offset : -4309567794
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 36 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 37 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 38 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 39 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 40 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup,
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 497796854189; DSPS: 16452579; Offset : -4309564264
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 41 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 42 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7092): 
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): ok 43 should be equal
I/jxcore-log( 7092): 
I/jxcore-log( 7092): ok 44 should be equal
I/jxcore-log( 7092): 
,I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
I/jxcore-log( 7092): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7092): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 517798731369; DSPS: 17108001; Offset : -4309579173
,I/jxcore-log( 7092): # teardown
I/jxcore-log( 7092): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019698884.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019698884.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3787): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019698884.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019698884.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019698884.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019698884.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80962c20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80962c20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639383838342e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639383838342e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639383838341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639383838341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/jxcore-log( 7092): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639383838341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639383838341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
,D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
I/jxcore-log( 7092): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699002.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699002.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699002.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699002.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699002.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699002.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f14e1c82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f14e1c82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393030322e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393030322e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393030321f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393030321f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
I/jxcore-log( 7092): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/LGWifiP2pService( 1036): discovery change broadcast true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 7092): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699053.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393030321f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699053.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393030321f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699053.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699053.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699053.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699053.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=-26ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
,D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=-43ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-43ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/jxcore-log( 7092): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c3b51e76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c3b51e76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393035332e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.Discov,eryManager( 7092): setState: NOT_STARTED
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393035332e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393035331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/jxcore-log( 7092): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393035331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699106.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393035331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393035331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699106.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
W/BluetoothAdapter( 7092): getBluetoothService(), called with no BluetoothManagerCallback
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699106.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699106.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699106.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699106.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6ec8bbb8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6ec8bbb8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393130362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393130362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393130361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393130361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/jxcore-log( 7092): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393130361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393130361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7092): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699134.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73,:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699134.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699134.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699134.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699134.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699134.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@89acfe76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@89acfe76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393133342e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393133342e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393133341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393133341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger s,ince one is already pending
I/jxcore-log( 7092): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7092): stop
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1036): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393133341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393133341f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/jxcore-log( 7092): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699156.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699156.7092","ra":"58:,3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699156.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699156.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699156.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699156.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b883746e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b883746e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393135362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393135362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393135361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393135361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/W,ifiNative-p2p0( 1036): P2P_FIND 120: returned true
I/jxcore-log( 7092): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
D/LGWifiP2pService( 1036): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 7092): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393135361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393135361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiMonitor( 1036): Event, [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699176.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699176.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699176.7092
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699176.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699176.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699176.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d60157ea target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d60157ea target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393137362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393137362e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393137361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393137361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/jxcore-log( 7092): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393137361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393137361f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 7092): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699203.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699203.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699203.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699203.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699203.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699203.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f8d5a3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f8d5a3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393230332e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393230332e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393230331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393230331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 7092): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393230331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/jxcore-log( 7092): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393230331f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699229.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699229.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699229.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699229.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699229.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699229.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8114f52c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8114f52c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393232392e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393232392e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393232391f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393232391f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 7092): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393232391f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
I/jxcore-log( 7092): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393232391f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setDiscoveryMode: Mode set to WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699258.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699258.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7092): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): start: OK
I/io.jxcore.node.ConnectionHelper( 7092): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452019699258.7092
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7092): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452019699258.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): start: {"pi":"58:3F:54:73:64:C0","pn":"1452019699258.7092","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452019699258.7092","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24a58128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24a58128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393235382e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): start: Starting P2P device discovery...
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031393639393235382e37303932222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393235381f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393235381f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): start: OK
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): start: OK
I/wpa_supplicant( 2681): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1970): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 7092): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7092): 
I/io.jxcore.node.ConnectionHelper( 7092): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7092): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7092): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7092): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7092): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): stopWifiPeerDis,covery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7092): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393235381f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7092): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7092): setState: NOT_STARTED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031393639393235381f37303932222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2681): P2P-FIND-STOPPED 
I/jxcore-log( 7092): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7092): 
D/WfdsMonitor( 1970): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/jxcore-log( 7092): # setup
I/jxcore-log( 7092): 
,I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.,thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7092): onConnectionManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7092): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7092): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7092): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7092): Service requests cleared successfully
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 537801120633; DSPS: 17763439; Offset : -4309570150
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 557802897344; DSPS: 18418857; Offset : -4309563562
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3252b4e5 type 2 when 573999 android} when 573999
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,I/BooksSync( 6983): Starting books sync
,D/BooksSync( 6983): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6366693050739182348&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 31943(1755KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 3.127ms total 175.675ms
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6366693050739182348&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6366693050739182348&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 577804611243; DSPS: 19074273; Offset : -4309558570
,E/BooksSync( 6983): Soft error: 
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6366693050739182348&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
,E/BooksSync( 6983): Sync error
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6366693050739182348&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
I/BooksSync( 6983): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 573999, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 597806509047; DSPS: 19729695; Offset : -4309553011
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{12e31027 type 2 when 604191 android} when 604191
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 617808500810; DSPS: 20385121; Offset : -4309575436
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 637810838928; DSPS: 21040557; Offset : -4309556497
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,I/ActivityManager( 1036): Killing 6249:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10044/pid_6249/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 657813093035; DSPS: 21695991; Offset : -4309560560
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/HeadsetStateMachine( 3787): Disconnected process message: 10, size: 0
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 677814752455; DSPS: 22351406; Offset : -4309579815
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 697816636718; DSPS: 23006827; Offset : -4309557202
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 717818553585; DSPS: 23662250; Offset : -4309562891
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 737821103630; DSPS: 24317694; Offset : -4309576271
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 757823057945; DSPS: 24973118; Offset : -4309575184
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 777824937312; DSPS: 25628539; Offset : -4309557286
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 797826587929; DSPS: 26283953; Offset : -4309554618
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 817828461880; DSPS: 26939375; Offset : -4309572862
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 837830517548; DSPS: 27594802; Offset : -4309561792
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 857831904313; DSPS: 28250207; Offset : -4309548266
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 877833853628; DSPS: 28905632; Offset : -4309582412
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 897835169037; DSPS: 29561035; Offset : -4309579467
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 917837122467; DSPS: 30216459; Offset : -4309579162
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 937839084803; DSPS: 30871883; Offset : -4309569977
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{1ec3f2d4 type 2 when 942695 com.android.bluetooth} when 942695
,W/bt-smp  ( 3787): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3787): Plain text(LSB ~ MSB) = a1 a7 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3787): Encrypted text(LSB ~ MSB) = a1 ad 2e 73 54 07 e4 d8 64 16 ca eb 24 6d b8 14 
W/bt-btm  ( 3787): Stopping oneshot timer
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 957841166723; DSPS: 31527311; Offset : -4309563278
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 977843401923; DSPS: 32182744; Offset : -4309555862
I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated(),
I/[SystemUI]DateView( 1470): called onTimeUpdated(),
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 997845430613; DSPS: 32838171; Offset : -4309571824
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1017847071804; DSPS: 33493585; Offset : -4309578503
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1037848812837; DSPS: 34149002; Offset : -4309576816
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1057850871477; DSPS: 34804429; Offset : -4309563036
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1077852728760; DSPS: 35459850; Offset : -4309567351
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1097854354846; DSPS: 36115263; Offset : -4309558749
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{31632c7d type 2 when 1104264 android} when 1104264
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,I/BooksSync( 6983): Starting books sync
D/BooksSync( 6983): started syncMyEbooks
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
W/ApiaryClient( 6983): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6801514622746875531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6801514622746875531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2132): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2132): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2132): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2132): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2132): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{137f15ea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6801514622746875531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
E/BooksSync( 6983): Soft error: 
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6801514622746875531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
,E/BooksSync( 6983): Sync error
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6801514622746875531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
I/BooksSync( 6983): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1104264, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1117856932130; DSPS: 36770708; Offset : -4309575303
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{41256ff type 2 when 1135092 android} when 1135092
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1137858377487; DSPS: 37426115; Offset : -4309564324
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1157860991855; DSPS: 38081561; Offset : -4309574572
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1177862670910; DSPS: 38736976; Offset : -4309573933
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1197864482204; DSPS: 39392395; Offset : -4309563149
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 3787): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1036): battery changed pluggedType: 2
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1217866398030; DSPS: 40047818; Offset : -4309569904
,I/UsageStatsService( 1036): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7598): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7598): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@d0a3f7
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1237868483751; DSPS: 40703246; Offset : -4309559328
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1257871121348; DSPS: 41358693; Offset : -4309576863
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1277873003007; DSPS: 42014114; Offset : -4309556620
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1297874601489; DSPS: 42669527; Offset : -4309575700
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1317876433981; DSPS: 43324947; Offset : -4309574106
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1337878422984; DSPS: 43980372; Offset : -4309569084
I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1357879826361; DSPS: 44635778; Offset : -4309569309
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1377882427448; DSPS: 45291223; Offset : -4309562345
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1397884240044; DSPS: 45946643; Offset : -4309580726
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1417886340089; DSPS: 46602071; Offset : -4309555928
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1437887913050; DSPS: 47257483; Offset : -4309569803
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1457889785906; DSPS: 47912904; Offset : -4309558649
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1477892411993; DSPS: 48568350; Offset : -4309556866
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1497894004069; DSPS: 49223763; Offset : -4309582351
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1517895899998; DSPS: 49879185; Offset : -4309578512
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1537897875042; DSPS: 50534609; Offset : -4309556463
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1557899766077; DSPS: 51190031; Offset : -4309557622
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1577901727632; DSPS: 51845456; Offset : -4309579710
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged(),
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1597903369916; DSPS: 52500869; Offset : -4309554753
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1617905180377; DSPS: 53156289; Offset : -4309575451
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1637906784015; DSPS: 53811701; Offset : -4309558779
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1657908199945; DSPS: 54467108; Offset : -4309577019
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1677909813531; DSPS: 55122521; Offset : -4309580944
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3787): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1697912473003; DSPS: 55777968; Offset : -4309576578
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1717914054662; DSPS: 56433380; Offset : -4309581833
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1737915664237; DSPS: 57088792; Offset : -4309559094
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1757917302666; DSPS: 57744206; Offset : -4309568616
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1777919247139; DSPS: 58399630; Offset : -4309577293
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1797921863225; DSPS: 59055075; Offset : -4309555175
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1817923572801; DSPS: 59710491; Offset : -4309554662
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1837925205189; DSPS: 60365905; Offset : -4309570196
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,W/bt-smp  ( 3787): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3787): Plain text(LSB ~ MSB) = ab fe 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3787): Encrypted text(LSB ~ MSB) = 79 f6 79 c8 06 e2 5a 78 52 67 9b 84 88 ec 65 05 
,W/bt-btm  ( 3787): Stopping oneshot timer
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{13152b15 type 2 when 1842722 com.android.bluetooth} when 1842722
I/ProcessStatsService( 1036): Prepared write state in 30ms
,I/ProcessStatsService( 1036): Prepared write state in 20ms
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
,I/ProcessStatsService( 1036): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-55-29.bin
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1857927207993; DSPS: 61021331; Offset : -4309581475
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3a61ee2a type 2 when 1202675 com.google.android.gms} when 1202675
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{10bf641b type 0 when 1452020548988 com.google.android.gms} when 1452020548988
,D/GCM     ( 2132): Message class com.google.f.a.a.i
,D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2132): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2132): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2132): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2132): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2367): Aggregate from 1452018748933 (log), 1452018748933 (data)
,I/art     ( 2132): Explicit concurrent mark sweep GC freed 49214(2MB) AllocSpace objects, 30(4MB) LOS objects, 51% free, 30MB/62MB, paused 1.573ms total 60.015ms
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1877929082465; DSPS: 61676752; Offset : -4309568653
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1897930760583; DSPS: 62332167; Offset : -4309569055
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1917932136044; DSPS: 62987572; Offset : -4309566832
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1937934084891; DSPS: 63642996; Offset : -4309570954
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1957935733476; DSPS: 64298410; Offset : -4309570500
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1977937289823; DSPS: 64953821; Offset : -4309570419
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1997938908878; DSPS: 65609234; Offset : -4309568822
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2017940919860; DSPS: 66264660; Offset : -4309572052
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2037942823863; DSPS: 66920082; Offset : -4309560087
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2057944185313; DSPS: 67575487; Offset : -4309572084
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2077945860201; DSPS: 68230902; Offset : -4309575533
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2097947156340; DSPS: 68886304; Offset : -4309561262
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2117948730915; DSPS: 69541716; Offset : -4309573497
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=574929083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,I/ActivityManager( 1036): Killing 6640:com.wsandroid.suite.lge/1000 (adj 15): empty for 1824s
I/ActivityManager( 1036): Killing 7375:com.lge.formmanager/u0a26 (adj 15): empty for 1824s
,I/ActivityManager( 1036): Killing 6698:com.lge.email/u0a23 (adj 15): empty for 1824s
,I/ActivityManager( 1036): Killing 7340:com.lge.appbox.client/u0a11 (adj 15): empty for 1824s
,I/ActivityManager( 1036): Killing 7180:com.android.settings/1000 (adj 15): empty for 1827s
,I/ActivityManager( 1036): Killing 7220:com.lge.sync/1000 (adj 15): empty for 1827s
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6640/cgroup.procs: No such file or directory
,I/DigitalAppWidgetProvider( 7598): onReceive: com.android.deskclock.ON_QUARTER_HOUR
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_7340/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7180/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7220/cgroup.procs: No such file or directory
W/libprocessgroup( 1036): failed to open /acct/uid_10026/pid_7375/cgroup.procs: No such file or directory
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6698/cgroup.procs: No such file or directory
D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7598): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@d0a3f7
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=574929083 [*alarm*], flags=0x0
I/ActivityManager( 1036): Killing 7398:com.android.chrome/u0a57 (adj 15): empty for 1824s
W/libprocessgroup( 1036): failed to open /acct/uid_10057/pid_7398/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
