#### Test 50650278d0426ce_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 157369917442; DSPS: 5297838; Offset : -4318530946
,D/AndroidRuntime( 6928): 
D/AndroidRuntime( 6928): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6928): CheckJNI is OFF
D/AndroidRuntime( 6928): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1959): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{2f4d44fd #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{2f4d44fd #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6943 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6928): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{1c492aee co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{384ffb8f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6943): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6943): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6943): Loading: webviewchromium
I/LibraryLoader( 6943): Time to load native libraries: 4 ms (timestamps 711-715)
I/LibraryLoader( 6943): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6943): Binding Chromium to main looper Looper (main, tid 1) {2a23761e}
I/LibraryLoader( 6943): Expected native library version number "",actual native library version number ""
I/chromium( 6943): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6943): Initializing chromium process, renderers=0
W/art     ( 6943): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6943): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6943): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6943): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb54f5020, uid 10311
I/Adreno-EGL( 6943): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6943): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6943): Build Date: 12/12/14 금
I/Adreno-EGL( 6943): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6943): Remote Branch: 
I/Adreno-EGL( 6943): Local Patches: 
I/Adreno-EGL( 6943): Reconstruct Branch: 
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1725319f:true
W/chromium( 6943): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6943): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6943): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6943): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6943): CordovaWebView is running on device made by: LGE
W/art     ( 6943): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6943): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6943): Render dirty regions requested: true
I/OpenGLRenderer( 6943): Initialized EGL, version 1.4
D/OpenGLRenderer( 6943): Enabling debug mode 0
D/Atlas   ( 6943): Validating map...
D/SplitWindow( 1039): check instance of lgWin Window{1bda00a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20eb52e1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1455): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1455): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1455):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1455): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6943): LgDataFeature() Constructor: none
D/LgDataFeature( 6943): LgDataFeature() Constructor Done, null
I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +584ms (total +683ms)
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{799a5f2 u0 com.test.thalitest/.MainActivity t4} time:161087
I/Timeline( 6943): Timeline: Activity_idle id: android.os.BinderProxy@1a7a2ce time:161092
D/JsMessageQueue( 6943): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6943): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434877696
,D/JX-Cordova( 6943): jxcore cordova android initializing
E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6943): Initializing JXcore engine
W/jxcore-log( 6943): JXcore engine is ready
,W/jxcore-log( 6943): Starting JXcore engine
,W/.test.thalitest( 6943): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7437]" dev="sockfs" ino=7437 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6943): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 6943): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8614]" dev="sockfs" ino=8614 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6943): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6943): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32725]" dev="sockfs" ino=32725 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6943): Platform android
W/jxcore-log( 6943): 
W/jxcore-log( 6943): Process ARCH arm
W/jxcore-log( 6943): 
,I/jxcore-log( 6943): JXcore Cordova bridge is ready!
I/jxcore-log( 6943): 
W/jxcore-log( 6943): JXcore engine is started
,I/jxcore-log( 6943): Toggling radios to true
I/jxcore-log( 6943): 
,D/BluetoothAdapter( 6943): enable(): BT is already enabled..!
D/WifiService( 1039): New client listening to asynchronous messages
D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=6943, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=6943, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=6943, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1039): [164,184,563 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1039): reconnect pid=6943, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6943): Radios toggled
I/jxcore-log( 6943): 
I/wpa_supplicant( 2646): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1039): InitialState.processMessage what=4
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1039): InactiveState{ when=-21ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-21ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1039): SET ps 1: returned true
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7038 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1039): RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2125): Read error: ssl=0xaa6f8200: I/O error during system call, Connection timed out
V/NativeCrypto( 2125): SSL shutdown failed: ssl=0xaa6f8200: I/O error during system call, Broken pipe
E/WifiStateMachine( 1039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1039):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1039): [164,317,571 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
I/wpa_supplicant( 2646): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): ignoring duplicate network state non-change
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1039): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=164328
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=164328
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
,D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  314): Clearing all IP addresses on wlan0
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1039): hidePasspointNotification off =false
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=164392  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=164392  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=164399  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1039): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=164405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524292
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/ResourcesManager( 7038): Asset path '/system/framework/com.google.an,droid.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7038): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
,V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 7038): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7038): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 7038): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ResourcesManager( 7038): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService( 1039): Removing idletimer
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-185ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7038): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7038): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7038): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6430:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_6430/cgroup.procs: No such file or directory
,I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7038): LgDataFeature() Constructor: none
D/LgDataFeature( 7038): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
,I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7096 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1039): Killing 6624:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10008/pid_6624/cgroup.procs: No such file or directory
,W/ResourcesManager( 7096): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7096): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7096): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7096): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7096): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7096): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7096): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7096): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7096): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7096): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7096): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
,D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7096): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7096): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7096): LgDataFeature() Constructor: none
D/LgDataFeature( 7096): LgDataFeature() Constructor Done, null
,V/SoundPool( 7096): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7096): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7096): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7096): doLoad: loading sample sampleID=1
I/QRemote ( 7096): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 7096): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6746): QS Service created
,V/SoundPool( 7096): Start decode
V/MediaPlayer[Native]( 7096): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb54748c0, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6746): Service initServices...
D/UEI.SmartControl( 6746): QS start get config
E/QRemote ( 7096): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7096): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  319): setAudioSource() 
V/MediaPlayerService(  319): prepare
V/AwesomePlayer(  319): prepareAsync_l() 
V/MediaPlayerService(  319): wait for prepare
V/AwesomePlayer(  319): onPrepareAsyncEvent() 
V/AwesomePlayer(  319): initAudioDecoder() 
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AwesomePlayer(  319): getUseOffload() = 0 
V/OMXCodec(  319): OMXCodec::Create
V/OMXCodec(  319): findMatchingCodecs()
V/OMXCodec(  319): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  319): matchingCodecs.size()=1
V/OMXCodec(  319): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  319): LG Codec Adapter start
V/OMXCodec(  319): OMXCodec Createtor
V/OMXCodec(  319): setComponentRole
V/OMXCodec(  319): configureCodec protected=0
V/LGCodecAdapter(  319): called getLGCodecSpecificData
V/LGCodecOSAL(  319): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMSG
V/LGCodecOSAL(  319): Not support LGCodec
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  319): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  319): Could not offload audio decode, try pcm offload
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3240 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c36a0 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb54748c0, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb54748c0, 1, 0, 0)
V/AudioCache(  319): prepared
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): start
V/AwesomePlayer(  319): play_l() 
V/AwesomePlayer(  319): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  319): createAudioPlayer_l
V/AwesomePlayer(  319): seekAudioIfNecessary_l() 
V/AwesomePlayer(  319): startAudioPlayer_l() 
D/AudioPlayer(  319): start of Playback, useOffload 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815424
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816304
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816544
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3240 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c37e0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb54748c0, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab504000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab505000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab506000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab507000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab508000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab509000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50a000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50b000, 0xb57d5000, 4096)
V/LGMDMManager( 7096): Create singleton instance
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50c000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50d000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50e000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab50f000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab510000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab511000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab512000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab513000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab514000, 0xb57d5000, 4096)
,V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab515000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab516000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab517000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab518000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab519000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51a000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51b000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51c000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51d000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51e000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab51f000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab520000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab521000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab522000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab523000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab524000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab525000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab526000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab527000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab528000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab529000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52a000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52b000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52c000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52d000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52e000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab52f000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab530000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab531000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab532000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab533000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab534000, 0xb57d5000, 4096)
V/AudioCache(  319): write(0xb57d5000, 4096)
V/AudioCache(  319): memcpy(0xab535000, 0xb57d5000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb57d5000, 280)
V/AudioCache(  319): memcpy(0xab536000, 0xb57d5000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb54748c0, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb54748c0, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  319): Pause Playback at 1068125
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb54748c0, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57c37e0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3240 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57c35b0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 7096): close(31)
V/SoundPool( 7096): pointer = 0x9fe39000, size = 205080, sampleRate = 48000, numChannels = 2
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{1ef5ecaa type 0 when 1449681254231 android} when 1449681254231
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{124dc09b type 2 when 165376 com.google.android.gms} when 165376
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9127
E/WifiStateMachine( 1039):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:101101] from screen [on:0 period:-2017690994]
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/UEI.SmartControl( 6746): Supports setup maps: true
,D/UEI.SmartControl( 6746): QS start statue = true Error code = 0
I/UEI.SmartControl( 6746): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6746): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6746): ### init IR Blaster...
D/serial_port( 6746): Configuring serial port
E/UEI.SmartControl( 6746): UEIBLaster setting for 616
I/UEI.SmartControl( 6746): Setting serial record hearder size = 2
I/UEI.SmartControl( 6746): configuring settings for MAXQ616
I/UEI.SmartControl( 6746): Get version...
D/UEI.SmartControl( 6746): serial port data available: 21
,D/UEI.SmartControl( 6746): MAXQ616 A2-X4 software.,
I/UEI.SmartControl( 6746): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6746): QS saving settings...
,D/UEI.SmartControl( 6746): IR Blaster version: 25672567
D/UEI.SmartControl( 6746): serial port data available: 4
,I/UEI.SmartControl( 6746): Device manager: loading config....
,D/UEI.SmartControl( 6746): ----------- loading internal config...
,W/ContextImpl( 6746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6746): Services init done
D/UEI.SmartControl( 6746): QS Service init finished
D/UEI.SmartControl( 6746): QS Service version name: 2.1.91
D/UEI.SmartControl( 6746): QS Service version code: 201091
D/UEI.SmartControl( 6746): Service requested: Control
E/UEI.SmartControl( 6746): Loading SETTINGS...
D/UEI.SmartControl( 6746): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6746): Internal service binding...
I/QRemote ( 7096): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6746): ------ IControl API: 11
D/UEI.SmartControl( 6746): File observer start...
E/UEI.SmartControl( 6746): IR Port is disabled: false
D/UEI.SmartControl( 6746): Starting file observer...
I/UEI.SmartControl( 6746): Registering callback...
I/UEI.SmartControl( 6746): ------ IControl API: 19
D/UEI.SmartControl( 6746): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6746): Registering Services Ready callback...
,I/UEI.SmartControl( 6746): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6746): -----service ready thread exits
I/QRemote ( 7096): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7096): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7096): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7096): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7096): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6746): ------ IControl API: 8
D/QRemote ( 7096): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7096): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7096): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7096): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7096): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7096): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7096): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7096): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7096): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,D/QRemote ( 7096): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7096): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449681255430]
D/QRemote ( 7096): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1039): Killing 6050:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7096): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6050/cgroup.procs: No such file or directory
,V/QRemote ( 7096): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7096): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3d1e2976 type 2 when 166194 android} when 166194
,I/wpa_supplicant( 2646): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=166412  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=166415  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2646): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=166509  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=166510  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166510
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166510
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166510
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166511
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166511
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=166511  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/wpa_supplicant( 2646): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2646): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast ac,tion 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=166524  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=166530  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=166530  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=166531
,E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=166531
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
D/UsbSettingsControl( 7038): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7038): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7038): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1039): Got NetworkAgent Messenger
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
,D/ConnectivityService( 1039): NetworkAgent connected
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{17ceb6bd type 0 when 1449681256203 com.android.vending} when 1449681256203
,D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 2
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166575  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166575  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166576  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/DhcpStateMachine( 1039): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166583  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166583  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166584  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21891d64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21891d64 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1039): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1039): SET ps 1: returned true
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1039): ignoring duplicate network state non-change
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 1
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1039): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1455): mWifiConnected = true, mWifiLevel = 0
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1039): Switching to ,new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524290
V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
W/dsqn    ( 7160): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7160): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,E/DSQN    ( 7160): DSQN ssw
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7096): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7096): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7096): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7096): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7096): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7096): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:14:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681256471], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681256446]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524290
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/dhcpcd  ( 7166): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7166): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/dhcpcd  ( 7166): version 5.5.6 starting
E/dhcpcd  ( 7166): get_duid: m
D/dhcpcd  ( 7166): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7166): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7166): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7166): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7166): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7166): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 7166): wlan0: sending REQUEST (xid 0xd02aef38), next in 3.99 seconds
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6180): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6180): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6180): [1] 5.onFinished: Scheduling replication attempt 4.
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5833): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5833): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7192 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{19ffc92d type 2 when 167488 com.google.android.gms} when 167488
I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7210 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7192): onCreate
,W/AppUp4:DB( 7192):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7192):  setFingerPrint start
I/AppUp4:DB( 7192):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7192):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7192):  SDK version = 21
I/AppUp4:DB( 7192):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7192): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7192): onReceive
I/ReaderUtils( 7210): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,D/LgDataFeature( 7192): LgDataFeature() Constructor: none
,D/LgDataFeature( 7192): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7192): Context : android.app.ReceiverRestrictedContext@2c7194cc
D/AppUp4:CustFacade( 7192): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7192): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7192): begin check event
I/AppUp4:CustModeStarterReceiver( 7192): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7192): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7192): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7192): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7192): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 6070:com.android.contacts/u0a19 (adj 15): empty #17
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_6070/cgroup.procs: No such file or directory
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3391): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3391): DownloadService onCreate
I/DownloadManager( 3391): in removeSpuriousFiles
V/DownloadManager( 3391): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@1bdf12a9 on behalf of 3391
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,D/eas_req ( 6649): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3391): in trimDatabase
V/DownloadManager( 3391): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3391): DownloadService onStartCommand
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@9f5755c on behalf of 3391
V/DownloadManager( 3391): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@286d3065 on behalf of 3391
V/DownloadManager( 3391): processing inserted download 1
V/DownloadManager( 3391): processing inserted download 4
V/DownloadManager( 3391): processing inserted download 7
V/DownloadManager( 3391): processing inserted download 8
V/DownloadManager( 3391): processing inserted download 9
V/DownloadManager( 3391): processing inserted download 10
V/DownloadManager( 3391): processing inserted download 16
V/DownloadManager( 3391): processing inserted download 17
,V/DownloadManager( 3391): processing inserted download 18
,V/DownloadManager( 3391): processing inserted download 21
W/GAV2    ( 7210): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7240 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 26.356ms
,V/DownloadManager( 3391): DownloadService onDestroy
I/BooksApp( 7210): Created application version: 3.2.35 (30235)
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 19.905ms
I/HubEmail( 6649): JNI_OnLoad()
I/HubEmail( 6649): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6649): registerNatives()
I/HubEmail( 6649): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6649): registerNativeMethods()
I/HubEmail( 6649): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6649): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.017ms
,W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/BooksSync( 7210): Starting books sync
,I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7269 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7166): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
I/dhcpcd  ( 7166): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 7166): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 7166): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7166): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7166): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7166): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7166): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7166): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
E/WifiStateMachine( 1039):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1039): identical MTU - not setting
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524295
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7300 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6094:com.android.gallery3d/u0a27 (adj 15): empty #17
D/BooksSync( 7210): started syncMyEbooks
V/FormManager( 7240): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7240): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_6094/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Killing 6550:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1039): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
I/art     ( 1039): Explicit concurrent mark sweep GC freed 96268(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.803ms total 132.799ms
,I/ActivityManager( 1039): Killing 6681:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7338 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_6550/cgroup.procs: No such file or directory
W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6681/cgroup.procs: No such file or directory
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE),
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
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
,W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
I/art     ( 7338): Almond Protected OAT
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,D/WeatherApplication( 7338): removeAccount
D/WeatherApplication( 7338): Account.length = 0
E/WeatherApplication( 7338): OPERATOR:OPEN
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:18
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:18
I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7369 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6709:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3145854418675942353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
,W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_6709/cgroup.procs: No such file or directory
,W/ProcessCpuTracker( 1039): Skipping unknown process pid 7359
W/ProcessCpuTracker( 1039): Skipping unknown process pid 7362
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7369): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7369): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7369): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7369): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7369): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7369): Loading: webviewchromium
,I/LibraryLoader( 7369): Time to load native libraries: 4 ms (timestamps 9499-9503)
I/LibraryLoader( 7369): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7369): Binding Chromium to main looper Looper (main, tid 1) {269403e7}
I/LibraryLoader( 7369): Expected native library version number "",actual native library version number ""
I/chromium( 7369): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7369): Initializing chromium process, renderers=0
W/art     ( 7369): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  319): registerClient() client 0xb54f5e60, uid 10093
W/AudioManagerAndroid( 7369): Requires BLUETOOTH permission
,W/chromium( 7369): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7369): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7369): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7369): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7369): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7369): Build Date: 12/12/14 금
I/Adreno-EGL( 7369): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7369): Remote Branch: 
I/Adreno-EGL( 7369): Local Patches: 
I/Adreno-EGL( 7369): Reconstruct Branch: 
,I/NSApplication( 7369): Starting up...
,V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,I/ActivityManager( 1039): Killing 6795:com.lge.eula/1000 (adj 15): empty #17
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6795/cgroup.procs: No such file or directory
,D/Tethering( 1039): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5833): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7192): onReceive
D/AppUp4:CustFacade( 7192): Context : android.app.ReceiverRestrictedContext@2c7194cc
D/AppUp4:CustFacade( 7192): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7192): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7192): begin check event
I/AppUp4:CustModeStarterReceiver( 7192): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3391): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3391): DownloadService onCreate
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3391): in removeSpuriousFiles
,V/DownloadManager( 3391): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@1abb1eb on behalf of 3391
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3391): in trimDatabase
V/DownloadManager( 3391): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@d128b48 on behalf of 3391
,E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3391): DownloadService onStartCommand
V/DownloadManager( 3391): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@59181c7 on behalf of 3391
V/DownloadManager( 3391): processing inserted download 1
V/DownloadManager( 3391): processing inserted download 4
,V/DownloadManager( 3391): processing inserted download 7
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:19
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@230cd62a
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3391): processing inserted download 8
V/DownloadManager( 3391): processing inserted download 9
V/DownloadManager( 3391): processing inserted download 10
W/Kids    ( 2354): [AccountUtils] Account not ready
W/Kids    ( 2354): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2354): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2354): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3391): processing inserted download 16
D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
V/DownloadManager( 3391): processing inserted download 17
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:19
V/DownloadManager( 3391): processing inserted download 18
V/DownloadManager( 3391): processing inserted download 21
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
V/DownloadManager( 3391): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/FormManager( 7240): There are no updated forms. The schedule will be deleted.
V/FormManager( 7240): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7192): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7192): onReceive
D/AppUp4:CustFacade( 7192): Context : android.app.ReceiverRestrictedContext@2c7194cc
D/AppUp4:CustFacade( 7192): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7192): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7192): begin check event
I/AppUp4:CustModeStarterReceiver( 7192): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3391): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3391): DownloadService onCreate
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3391): in removeSpuriousFiles
V/DownloadManager( 3391): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3391): DownloadService onStartCommand
,V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@311a7363 on behalf of 3391
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
V/DownloadManager( 3391): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3391): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3391): in trimDatabase
V/DownloadManager( 3391): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LgeQuickCoverNLService( 1404): onNotificationPosted
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
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
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@18fd7b60 on behalf of 3391
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Kids    ( 2354): [AccountUtils] Account not ready
W/Kids    ( 2354): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2354): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2354): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3391): created cursor android.database.sqlite.SQLiteCursor@2bc4f819 on behalf of 3391
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = true
D/PhoneState( 3333): setPdpRejectCasuse : false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/DownloadManager( 3391): processing inserted download 1
V/DownloadManager( 3391): processing inserted download 4
V/DownloadManager( 3391): processing inserted download 7
V/DownloadManager( 3391): processing inserted download 8
,V/DownloadManager( 3391): processing inserted download 9
W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
V/DownloadManager( 3391): processing inserted download 10
D/QuickStatusbarLayout( 1404): Notification difference=198
V/DownloadManager( 3391): processing inserted download 16
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
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
D/WeatherAncestor( 7338): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:19
V/DownloadManager( 3391): processing inserted download 17
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/DownloadManager( 3391): processing inserted download 18
D/Weather.Utils( 7338): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7338): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7338): 2 : This is isUpdating : false
D/WeatherAncestor( 7338): connectivity changed - connection : true
D/WeatherService( 7338): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@230cd62a
D/ForecastDataCache( 7338): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7338): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7338): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7338): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7338): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:14:19
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/DownloadManager( 3391): processing inserted download 21
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/DownloadManager( 3391): DownloadService onDestroy
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
W/ApiaryClient( 7210): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3145854418675942353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/FormManager( 7240): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7240): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/Kids    ( 2354): [AccountUtils] Account not ready
W/Kids    ( 2354): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2354): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2354): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2354): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2354): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2354): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2125): Connected
,D/GCM     ( 2125): Message class com.google.f.a.a.p
D/UEI.SmartControl( 6746): Internal timer expired: 4
D/UEI.SmartControl( 6746): unbind internal service
,D/serial_port( 6746): close(fd = 24)
,I/UEI.SmartControl( 6746): Serial port is closed.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2125): Explicit concurrent mark sweep GC freed 33924(1973KB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.762ms total 50.953ms
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
W/ApiaryClient( 7210): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3145854418675942353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
,I/jxcore-log( 6943): Test app app.js loaded
I/jxcore-log( 6943): 
,I/chromium( 6943): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 6943): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6943): 
,I/chromium( 6943): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6943): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6943): 
,E/BooksSync( 7210): Soft error: 
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3145854418675942353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
,E/BooksSync( 7210): Sync error
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3145854418675942353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
I/BooksSync( 7210): Finished books sync
I/ActivityManager( 1039): Killing 6826:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166194, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6826/cgroup.procs: No such file or directory
,I/GAV2    ( 7210): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 7369): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 177372059936; DSPS: 5953268; Offset : -4318524318
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{216c85eb type 2 when 184588 com.google.android.gms} when 184588
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{26a461e1 type 0 when 1449681276564 com.android.vending} when 1449681276564
,V/QRemote ( 7096): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7096): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9127
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/VacuumService( 2125): Vacuum at: now=1449681281801 tag=VacuumService
,I/GoogleURLConnFactory( 2125): Using platform SSLCertificateSocketFactory
,W/Uploader( 2125): No account for auth token provided
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1039): Explicit concurrent mark sweep GC freed 31071(1456KB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 1.889ms total 127.933ms
,D/Finsky  ( 6180): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6180): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6180): [1] 5.onFinished: Scheduling replication attempt 5.
W/Uploader( 2125): No account for auth token provided
,W/Uploader( 2125): No account for auth token provided
,W/Uploader( 2125): No account for auth token provided
,W/Uploader( 2125):  no longer exists, so no auth token.
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 197374226179; DSPS: 6608699; Offset : -4318525215
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{15b58d89 type 2 when 197601 android} when 197601
,E/WifiStateMachine( 1039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7528 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7528): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7528): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2990ca59
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
I/ActivityManager( 1039): Killing 6855:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_6855/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 217376710858; DSPS: 7264140; Offset : -4318512172
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{15298daf type 0 when 1449681302188 com.android.vending} when 1449681302188
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6180): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6180): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6180): [1] 5.onFinished: Giving up after 6 failures.
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{131feaf9 type 2 when 227624 android} when 227624
,I/BooksSync( 7210): Starting books sync
,D/BooksSync( 7210): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1669348877427684201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1669348877427684201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1669348877427684201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
E/BooksSync( 7210): Soft error: 
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1669348877427684201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
,E/BooksSync( 7210): Sync error
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1669348877427684201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
I/BooksSync( 7210): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202626, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 237378904184; DSPS: 7919572; Offset : -4318516450
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{4d60a4c type 2 when 238550 android} when 238550
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257381277927; DSPS: 8575010; Offset : -4318523026
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{90dba95 type 2 when 257675 android} when 257675
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277383158283; DSPS: 9230431; Offset : -4318504191
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2df007aa type 2 when 291541 android} when 291541
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
,I/BooksSync( 7210): Starting books sync
,D/BooksSync( 7210): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1404): Notification difference=198
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
W/ApiaryClient( 7210): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9101541106114053584&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
,W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9101541106114053584&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9101541106114053584&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
E/BooksSync( 7210): Soft error: 
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9101541106114053584&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
,E/BooksSync( 7210): Sync error
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9101541106114053584&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
I/BooksSync( 7210): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 291541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 297385355880; DSPS: 9885863; Offset : -4318503963
,I/[SystemUI]LGPowerUI( 1455): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1455): On Skip Timer : true
,D/LEDHandler( 1959): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1959): Battery Level Remaining: 100%
D/LEDHandler( 1959): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1455): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1455): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3805): Disconnected process message: 10, size: 0
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]BatterySaverHandler( 1455): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 317387551601; DSPS: 10541295; Offset : -4318505431
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{23e21744 type 2 when 321776 android} when 321776
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 337389536697; DSPS: 11196721; Offset : -4318534468
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 357391835962; DSPS: 11852156; Offset : -4318524073
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6180): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6180): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6180): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6180): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6180): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6180): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6180): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6180): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 28679(1270KB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 2.417ms total 189.777ms
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 377394004443; DSPS: 12507587; Offset : -4318522184
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 397396340998; DSPS: 13163024; Offset : -4318535562
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1e4d7086 type 2 when 415729 android} when 415729
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
,I/BooksSync( 7210): Starting books sync
,D/BooksSync( 7210): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1961561871440269939&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 417397796407; DSPS: 13818431; Offset : -4318512811
,W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1961561871440269939&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7210): Authentication error
E/BooksAccountManager( 7210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7210): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7210): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{1b6913f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7210): Error response from books API: {
W/ApiaryClient( 7210):  "error": {
W/ApiaryClient( 7210):   "errors": [
W/ApiaryClient( 7210):    {
W/ApiaryClient( 7210):     "domain": "global",
W/ApiaryClient( 7210):     "reason": "required",
W/ApiaryClient( 7210):     "message": "Login Required",
W/ApiaryClient( 7210):     "locationType": "header",
W/ApiaryClient( 7210):     "location": "Authorization"
W/ApiaryClient( 7210):    }
W/ApiaryClient( 7210):   ],
W/ApiaryClient( 7210):   "code": 401,
W/ApiaryClient( 7210):   "message": "Login Required"
W/ApiaryClient( 7210):  }
W/ApiaryClient( 7210): }
,W/ApiaryClient( 7210): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1961561871440269939&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7210): Headers:
W/ApiaryClient( 7210): accept-encoding: [gzip]
W/ApiaryClient( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7210): gdata-version: 2
E/BooksSync( 7210): Soft error: 
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1961561871440269939&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
,E/BooksSync( 7210): Sync error
E/BooksSync( 7210): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7210): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1961561871440269939&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7210): Headers:
E/BooksSync( 7210): accept-encoding: [gzip]
E/BooksSync( 7210): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7210): gdata-version: 2
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7210): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7210): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7210): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7210): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7210): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7210): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7210): {
E/BooksSync( 7210):  "error": {
E/BooksSync( 7210):   "errors": [
E/BooksSync( 7210):    {
E/BooksSync( 7210):     "domain": "global",
E/BooksSync( 7210):     "reason": "required",
E/BooksSync( 7210):     "message": "Login Required",
E/BooksSync( 7210):     "locationType": "header",
E/BooksSync( 7210):     "location": "Authorization"
E/BooksSync( 7210):    }
E/BooksSync( 7210):   ],
E/BooksSync( 7210):   "code": 401,
E/BooksSync( 7210):   "message": "Login Required"
E/BooksSync( 7210):  }
E/BooksSync( 7210): }
E/BooksSync( 7210): 
E/BooksSync( 7210): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7210): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7210): 	... 8 more
I/BooksSync( 7210): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 415729, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 6943): Toggling radios to false
I/jxcore-log( 6943): 
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27c08740 mBinding = false
,D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3805): [BTUI] Precleanup
D/BluetoothAdapterState( 3805): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3805): Setting state to 13
I/BluetoothAdapterState( 3805): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3805): onBluetoothDisable()
I/BluetoothAdapterState( 3805): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3805): Scan Mode:20
,D/BluetoothAdapterState( 3805): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 3805): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3805): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3805): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3805): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3805): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3805): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3805): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3805): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 3805): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 3805): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BtOppRfcommListener( 3805): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3805): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3805): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3805): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3805): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3805): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 12 -> 13
D/Ulp_jni ( 1039): JNI:system_update. Event-4
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7659 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=6943, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=6943, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/BluetoothMapService( 3805): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3805): STATE_TURNING_OFF
V/BluetoothMapService( 3805): Handler(): got msg=4
D/BluetoothMapService( 3805): MAP Service closeService in
D/BluetoothMapMasInstance( 3805): MAP Service shutdown
D/LGBluetoothMapAdapter( 3805): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3805): MAP Service closeService out
,V/BtOppService( 3805): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3805): stopping Accept Thread
V/BtOppRfcommListener( 3805): close mBtServerSocket
V/BtOppRfcommListener( 3805): waiting for thread to terminate
I/BtOppRfcommListener( 3805): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3805): done waiting for thread to terminate
D/LGBluetoothAPIService( 1959): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[SystemUI]BluetoothHandler( 1455): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
,E/WifiStateMachine( 1039):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6943): Radios toggled
I/jxcore-log( 6943): 
V/BtOppService( 3805): onDestroy
E/WifiStateMachine( 1039):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
D/LGBluetoothOppAdapter( 3805): [BTUI] LGBluetoothOppAdapter cleanup
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
W/ContextImpl( 7038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1039): SET ps 1: returned true
V/BluetoothPbapReceiver( 3805): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3805): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3805): ***********state = 13
D/CommandListener(  314): Clearing all IP addresses on wlan0
V/BluetoothPbapReceiver( 3805): ***********Calling start service!!!! with action = null
D/DhcpStateMachine( 1039): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapService( 3805): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3805): state: 13
V/BluetoothPbapService( 3805): Pbap Service closeService in
V/BluetoothPbapService( 3805): successfully stopped pbap service
V/BluetoothPbapService( 3805): Pbap Service closeService out
V/BluetoothPbapService( 3805): Pbap Service onDestroy
V/BluetoothPbapService( 3805): Pbap Service closeService in
V/BluetoothPbapService( 3805): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3805): [BTUI] cleanup
,D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fb6c81f:true
V/NativeCrypto( 2125): Read error: ssl=0xaa6f6400: I/O error during system call, Connection timed out
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
D/LGWifiP2pService( 1039): InactiveState{ when=-21ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-21ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1039): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ce160e2
V/NativeCrypto( 2125): SSL shutdown failed: ssl=0xaa6f6400: I/O error during system call, Broken pipe
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
,D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1039): SCAN_AVAILABLE : 1
D/WifiScanningService( 1039): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1039): SCAN_AVAILABLE : 1
D/RttService( 1039): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pDisablingState
D/LGWifiP2pService( 1039): P2pDisablingState{ when=-21ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): p2p socket connection lost
D/LGWifiP2pService( 1039): P2pDisabledState
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2646): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
V/WfdStateTracker( 1959): WfdStateTracker handleDirectStateChangedEvent: 0
D/LGWifiP2pService( 1039): P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WfdsService( 1959): WifiP2pState is changed : false
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/WfdsService( 1959): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1959): Set the WFDS Monitor: false
D/BluetoothManagerService( 1039): Message: 30
D/WfdsMonitor( 1959): WFDS Monitor is stopped
D/WfdsService( 1959): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1959): Received on exit socket, terminate
W/WfdsSession:Controller( 1959): DefaultState - msg [9441355] is not handled
E/CtrlSupplicant( 1959): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1959): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1959): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1959): DefaultState - msg [9445378] is not handled
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothManagerService( 1039): Message: 30
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/LocalBluetoothProfileManager( 7038): Adding local MAP profile
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothMap( 7038): Create BluetoothMap proxy object
D/BluetoothManagerService( 1039): Message: 30
D/BluetoothManagerService( 1039): Message: 30
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiNative-p2p0( 1039): doBoolean: TERMINATE
,D/WifiNative-p2p0( 1039): TERMINATE: returned true
D/WifiHS20( 1039): hidePasspointNotification off =false
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1959): WfdStateTracker handleDirectStateChangedEvent: 6
D/LocalBluetoothProfileManager( 7038): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7038):  get() - isFeatureLoaded : false
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1039): Removing idletimer
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
E/ConnectivityService( 1039): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/LGBluetoothUserBindClient( 7038): [BTUI] initUserBindClient
W/ContextImpl( 7038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2e6db907 type 2 when 430537 com.google.android.gms} when 430537
,D/DockEventReceiver( 7038): finishStartingService: stopping service
D/BluetoothInputDevice( 7038): Proxy object connected
D/HidProfile( 7038): Bluetooth service connected
D/BluetoothPan( 7038): BluetoothPAN Proxy object connected
D/PanProfile( 7038): Bluetooth service connected
D/BluetoothMap( 7038): Proxy object connected
,D/MapProfile( 7038): Bluetooth service connected
D/BluetoothMap( 7038): getConnectedDevices()
D/BluetoothMap( 7038): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7038): [BTUI] onServiceConnected
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ActivityThread( 7659): Failed to find provider info for com.lge.lgaccount.provider
I/wpa_supplicant( 2646): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2646): monitor socket send errors count : 1
I/wpa_supplicant( 2646): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1959-2\x00 that cannot receive messages
W/LG Account v2.2( 7659): No ProfileInfo entries
I/LG Account v2.2( 7659): isEnabled: false
I/Feature ( 7659): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7659): [Lifetracker]Country: EU
I/Feature ( 7659): [Lifetracker]Operator: OPEN
I/Feature ( 7659): [Lifetracker]Ranking support: false
I/Feature ( 7659): [Lifetracker]Comfort support: false
I/Feature ( 7659): [Lifetracker]Accessory: true
I/Feature ( 7659): [Lifetracker]Health device: true
I/Feature ( 7659): [Lifetracker]Extra Pedometer: false
I/Feature ( 7659): [Lifetracker]Blood glucose device: false
I/Feature ( 7659): [Lifetracker]Device Number: 3
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1039): Dropping event because (p2p0) is stopped
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGBluetoothAuthorization( 7038): [BTUI] cancel All Notification
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothPermissionRequest( 7038): onReceive
D/LGBluetoothAuthorization( 7038): [BTUI] cancel All Notification
,V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2646): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2646): USIM:  scard_deinit function
D/Tethering( 1039): InitialState.processMessage what=4
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=430598
E/WifiStateMachine( 1039):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=430599
E/WifiStateMachine( 1039):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=430599  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=430599  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1039):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
,I/ActivityManager( 1039): Killing 7192:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
,D/LGBluetoothResetSettingReceiver( 7038): return without doing reset settings.
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 2646): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1039):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
V/BluetoothOppReceiver( 3805): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3805): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3805): [BTUI] cancel opp active transfer file notification
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_7192/cgroup.procs: No such file or directory
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothFtpReceiver( 3805): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3805): BluetoothFtpReceiver Start Service
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,V/BluetoothFtpService( 3805): Ftp Service onStartCommand
V/BluetoothFtpService( 3805): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3805): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3805): Shutdown
V/BluetoothFtpService( 3805): successfully stopped ftp service
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapReceiver( 3805): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3805): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3805): SapReceiver onReceive 
V/BluetoothSapReceiver( 3805): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3805):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3805): Calling SAP service start service with action = null
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothFtpService( 3805): Ftp Service onDestroy
V/BluetoothFtpService( 3805): Ftp Service closeService
,V/BluetoothSapService( 3805): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3805): state: 13
,I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothSapService( 3805): Stopping SAP server process
V/BluetoothSapService( 3805): Sap Service closeSapService in
V/BluetoothSapService( 3805): Close listen Socket : 
V/BluetoothSapService( 3805): Close rfcomm Socket : 
V/BluetoothSapService( 3805): Close sapd  Socket : 
I/ActivityManager( 1039): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7712 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3805): Sap Service closeSapService out
V/BluetoothSapService( 3805): Sap Service onDestroy
V/BluetoothSapService( 3805): Sap Service closeSapService in
V/BluetoothSapService( 3805): Close listen Socket : 
V/BluetoothSapService( 3805): Close rfcomm Socket : 
V/BluetoothSapService( 3805): Close sapd  Socket : 
,V/BluetoothSapService( 3805): Sap Service closeSapService out
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiOffDelayIfNotUsed( 1039): stopMonitoring
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1959): Supplicant Connection state is changed : false
V/WfdStateTracker( 1959): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1959): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1959): Set the WFDS Monitor: false
D/WfdsMonitor( 1959): WFDS Monitor is stopped
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1824): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : this is not treated
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7072): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
,D/QRemote ( 7096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7240): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
W/ResourcesManager( 7712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/FormManager( 7240): Network unavailable.
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7038): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7038): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7038): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7038): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7038): [AUTORUN] setTetherStatus() : status=false
V/FormManager( 7240): Network unavailable.
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/AuthorizationBluetoothService( 2125): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/PCSuite ( 7072): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7072): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7072): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7038): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7240): Network not available. Please check & try again.
V/FormManager( 7240): Network unavailable.
D/WiFiOffLoadBroadcast( 7038): MCCMNC not supported: null
V/FormManager( 7240): Network unavailable.
I/ActivityManager( 1039): Killing 6649:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6649/cgroup.procs: No such file or directory
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{440a5a0 type 2 when 430924 com.google.android.gms} when 430924
,E/WifiStateMachine( 1039):  InitialState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_ON_QUIT 0 0
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3bbd7559 type 2 when 431146 com.google.android.gms} when 431146
,D/bt_hci_bdroid( 3805): cleanup
,I/bt_lpm  ( 3805): LPM is already off!!!
I/bt_userial_mct( 3805): exiting userial_read_thread
D/bt_userial_mct( 3805): Leaving userial_evt_read_thread()
W/bt-btif ( 3805): ag scb idx 1 not allocated
E/bt-btif ( 3805): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3805): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3805): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3805): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3805): L2CAP - PSM: 0x001b not found for deregistration
D/bt_userial_mct( 3805): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3805): hw_epilog_process
D/bt_hci_bdroid( 3805): cleanup Finalizing cleanup
D/bt_userial_mct( 3805): userial_close
E/bt_userial_mct( 3805): pthread_join() FAILED result:3
I/bt_vendor( 3805): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
E/bt-btif ( 3805): bta_gattc_deregister Deregister Failedm unknown client cif
,D/bt_hci_bdroid( 3805): set_power 0
I/bt_vendor( 3805): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 3805): bluetooth satus is on
I/bt_vendor( 3805): bt-vendor : resetting BT status
I/bt_vendor( 3805): Starting hciattach daemon
I/bt_vendor( 3805): try to set false
I/bt_vendor( 3805): Starting hciattach daemon
I/bt_vendor( 3805): try to set false
I/bt_vendor( 3805): cleanup
I/GKI_LINUX( 3805): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3805): GKI_exit_task 0 done
I/GKI_LINUX( 3805): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3805): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3805): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3805): [BTUI] LGBluetoothHfpAdapter cleanup
,W/LGBluetoothHeadsetServiceJni( 3805): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/HeadsetStateMachine( 3805): Exit Disconnected: -1
D/BluetoothHeadset( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1859): Proxy object disconnected
D/BluetoothHeadset( 1859): Proxy object disconnected
D/BluetoothHeadset( 1859): Proxy object disconnected
D/A2dpService( 3805): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3805): Exit Disconnected: -1
D/BluetoothAdapterState( 3805): Stopping profile services that were post enabled
D/LGBluetoothAvrcpQcomAdapter( 3805): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3805): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3805): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/HidService( 3805): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/BluetoothA2dp( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 2
D/HeadsetStateMachine( 3805): Unbinding service...
D/HeadsetPhoneState( 3805): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3805): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3805): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3805): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3805): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3805): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3805): [BTUI] LGBluetoothHfpAdapter cleanup
,D/HealthService( 3805): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/PanService( 3805): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/BtGatt.DebugUtils( 3805): handleDebugAction() action=null
D/BtGatt.GattService( 3805): Received stop request...Stopping profile...
D/BtGatt.GattService( 3805): stop()
D/BtGatt.AdvertiseManager( 3805): advertise clients cleared
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
D/BluetoothMapService( 3805): Received stop request...Stopping profile...
D/BluetoothMapService( 3805): stop()
,D/BluetoothMapEmailAppObserver( 3805): deinitObservers()
D/BluetoothMapEmailAppObserver( 3805): removeReceiver()
D/BluetoothAdapterService( 3805): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297ab315
I/BluetoothA2dpServiceJni( 3805): cleanupNative
I/GKI_LINUX( 3805): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3805): GKI_exit_task 2 done
I/GKI_LINUX( 3805): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3805): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3805): Cleaning up Bluetooth GID callback object
V/BluetoothMapService( 3805): Handler(): got msg=4
D/BluetoothMapService( 3805): MAP Service closeService in
D/LGBluetoothMapAdapter( 3805): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3805): MAP Service closeService out
D/BluetoothAdapterState( 3805): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3805): Setting state to 10
I/BluetoothAdapterState( 3805): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1039): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3805): Entering OffState
D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1039): onBluetoothStateChange: up=false
D/BluetoothPan( 7038): onBluetoothStateChange on: false
D/BluetoothA2dp( 1039): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
W/BluetoothHealthServiceJni( 3805): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3805): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3805): Cleaning up Bluetooth Health object
D/BluetoothInputDevice( 7038): onBluetoothStateChange: up=false
W/BluetoothPanServiceJni( 3805): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3805): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3805): cleanup()
D/BluetoothMapService( 3805): MAP Service closeService in
D/LGBluetoothMapAdapter( 3805): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3805): MAP Service closeService out
D/BluetoothInputDevice( 7038): Proxy object disconnected
D/HidProfile( 7038): Bluetooth service disconnected
D/BluetoothPbap( 7038): onBluetoothStateChange: up=false
,D/BluetoothMap( 7038): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1039): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1039): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1039): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@27c08740 mBinding = false
D/BluetoothManagerService( 1039): Sending unbind request.
,D/BluetoothMap( 7038): Proxy object disconnected
D/MapProfile( 7038): Bluetooth service disconnected
I/GKI_LINUX( 3805): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3805): GKI_exit_task 1 done
I/GKI_LINUX( 3805): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3805): cleanupNative: return from cleanup
I/art     ( 3805): --- WEIRD: removing null entry 246
W/art     ( 3805): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3805): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3805): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3805): System.exit called, status: 0
I/AndroidRuntime( 3805): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  319): 3805 died, releasing its sessions
V/AudioFlinger(  319):  pid 1859 @ 0
V/AudioFlinger(  319):  pid 3333 @ 1
V/AudioFlinger(  319):  pid 3333 @ 2
,D/LGBluetoothAPIService( 1959): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1959): Message: 101
E/LGBluetoothAPIService( 1959): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1959): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1959): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 7038): [BTUI] onServiceDisconnected
I/ActivityManager( 1039): Process com.android.bluetooth (pid 3805) has died
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 10999ms
,D/LGBluetoothAPIService( 1959): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1959): Message: 2
D/LGBluetoothAPIService( 1959): unbindAndFinish(): null mBinding = false
I/[SystemUI]BluetoothHandler( 1455): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothFeatureConfig( 7038): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 7038): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7038): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7038): [BTUI] clear device connection state
W/ContextImpl( 7038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapter( 1455): 230102500: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1455): 230102500: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager( 1039): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7767 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a,
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{17ac1ff type 2 when 431582 com.google.android.gms} when 431582
D/DockEventReceiver( 7038): finishStartingService: stopping service
,W/ResourcesManager( 7767): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7767): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7767): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7767): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7767): Loading JNI Library
,D/BluetoothAdapterApp( 7767): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d643ed2 Instance Count = 1
,D/BluetoothAdapterApp( 7767): onCreate
,D/ProfileConfigQcom( 7767): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7767): Adding HeadsetService
D/ProfileConfigQcom( 7767): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7767): Adding A2dpService
D/ProfileConfigQcom( 7767): [BTUI] HidService is supported
D/ProfileConfigQcom( 7767): Adding HidService
D/ProfileConfigQcom( 7767): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7767): Adding HealthService
D/LGBluetoothFeatureConfig( 7767): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7767): [BTUI] PanService is supported
D/ProfileConfigQcom( 7767): Adding PanService
D/ProfileConfigQcom( 7767): [BTUI] GattService is supported
D/ProfileConfigQcom( 7767): Adding GattService
D/ProfileConfigQcom( 7767): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7767): Adding BluetoothMapService
D/ProfileConfigQcom( 7767): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7767): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7767): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7767): ***********state = 10
,V/LGMDMManagerInternal( 7767): Create singleton instance
,D/LGBluetoothUserBindClient( 7038): [BTUI] onServiceConnected
,D/LGBluetoothAPIServer( 7767): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7767): [BTUI] onBind()
,D/LGBluetoothAPIService( 1959): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/BluetoothPermissionRequest( 7038): onReceive
D/LGBluetoothAPIService( 1959): Message: 100
D/LGBluetoothAPIService( 1959): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LGBluetoothUtils( 7038): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7038): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7038): return without doing reset settings.
D/LGBluetoothOppAdapter( 7767): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 7767): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7767): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7767): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7767): SapReceiver onReceive 
V/BluetoothSapReceiver( 7767): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7767):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7712): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 2125): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{129a7bcc type 2 when 432415 com.google.android.gms} when 432415
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1039): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5833): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7798 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NetworkMonitor( 5833): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7798): onCreate
W/AppUp4:DB( 7798):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7798):  setFingerPrint start
I/AppUp4:DB( 7798):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7798):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7798):  SDK version = 21
I/AppUp4:DB( 7798):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7798): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7798): onReceive
D/LgDataFeature( 7798): LgDataFeature() Constructor: none
D/LgDataFeature( 7798): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7798): Context : android.app.ReceiverRestrictedContext@2c7194cc
D/AppUp4:CustFacade( 7798): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7798): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7798): begin check event
I/AppUp4:CustModeStarterReceiver( 7798): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7798): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7798): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7798): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7798): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 7269:com.android.chrome/u0a57 (adj 15): empty #17
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1039): failed to open /acct/uid_10057/pid_7269/cgroup.procs: No such file or directory
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7837 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{4d988b8 type 2 when 434086 com.google.android.gms} when 434086
,W/ResourcesManager( 7837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7837): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7837): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7837): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7837): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7837): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7837): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7837): LgDataFeature() Constructor: none
D/LgDataFeature( 7837): LgDataFeature() Constructor Done, null
,D/eas_req ( 7837): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
,I/HubEmail( 7837): JNI_OnLoad()
I/HubEmail( 7837): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7837): registerNatives()
I/HubEmail( 7837): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7837): registerNativeMethods()
I/HubEmail( 7837): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7837): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7869 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7240): Network not available. Please check & try again.
I/art     (  348): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 24.891ms
,V/FormManager( 7240): Network unavailable.
,V/FormManager( 7240): Network unavailable.
,I/art     (  348): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.356ms total 28.526ms
I/ActivityManager( 1039): Killing 7300:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/Settings( 7837): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 25.756ms
W/libprocessgroup( 1039): failed to open /acct/uid_10062/pid_7300/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7897 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 7338:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10085/pid_7338/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7921 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 7369:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10093/pid_7369/cgroup.procs: No such file or directory
,I/art     ( 7921): Almond Protected OAT
,D/WeatherApplication( 7921): removeAccount
,D/WeatherApplication( 7921): Account.length = 0
E/WeatherApplication( 7921): OPERATOR:OPEN
D/WeatherAncestor( 7921): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:44
D/Weather.Utils( 7921): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7921): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7921): 2 : This is isUpdating : false
D/WeatherAncestor( 7921): connectivity changed - connection : true
D/WeatherService( 7921): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7921): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7921): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7921): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7921): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7921): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:45
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7939 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6767:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/LGWifiP2pService( 1039): P2pDisabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_6767/cgroup.procs: No such file or directory
E/WifiStateMachine( 1039):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1039):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7939): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7939): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7939): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7939): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7939): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7939): Loading: webviewchromium
,I/LibraryLoader( 7939): Time to load native libraries: 4 ms (timestamps 5933-5937)
I/LibraryLoader( 7939): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7939): Binding Chromium to main looper Looper (main, tid 1) {f625b01}
I/LibraryLoader( 7939): Expected native library version number "",actual native library version number ""
I/chromium( 7939): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7939): Initializing chromium process, renderers=0
W/art     ( 7939): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7939): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7939): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7939): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb54f5c80, uid 10093
W/AudioManagerAndroid( 7939): Requires BLUETOOTH permission
I/Adreno-EGL( 7939): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7939): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7939): Build Date: 12/12/14 금
I/Adreno-EGL( 7939): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7939): Remote Branch: 
I/Adreno-EGL( 7939): Local Patches: 
I/Adreno-EGL( 7939): Reconstruct Branch: 
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 52784(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 3.153ms total 191.241ms
,I/NSApplication( 7939): Starting up...
I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7994 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 7528:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10010/pid_7528/cgroup.procs: No such file or directory
,W/ResourcesManager( 7994): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2354): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2354): num queued entries: 0
I/iu.UploadsManager( 2354): num updated entries: 0
I/iu.SyncManager( 2354): NEXT; no task
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7798): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7798): onReceive
D/AppUp4:CustFacade( 7798): Context : android.app.ReceiverRestrictedContext@2c7194cc
D/AppUp4:CustFacade( 7798): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7798): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7798): begin check event
I/AppUp4:CustModeStarterReceiver( 7798): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSActivity( 2125): [ac] getting account id
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2125): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 7837): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
W/Settings( 7837): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7240): Network not available. Please check & try again.
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
D/WeatherAncestor( 7921): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:46
V/FormManager( 7240): Network unavailable.
,D/Weather.Utils( 7921): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7921): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7921): 2 : This is isUpdating : false
D/WeatherAncestor( 7921): connectivity changed - connection : true
D/WeatherService( 7921): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@230cd62a
D/ForecastDataCache( 7921): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7921): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7921): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7921): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7921): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:18:46
V/FormManager( 7240): Network unavailable.
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 437401697285; DSPS: 14473919; Offset : -4318519954
,I/GAV4    ( 7939): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1039): Killing 6180:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_6180/cgroup.procs: No such file or directory
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2722ad78 type 2 when 445934 android} when 445934
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 457403876132; DSPS: 15129350; Offset : -4318507855
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 477406022634; DSPS: 15784781; Offset : -4318527972
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 497408105178; DSPS: 16440209; Offset : -4318520700
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 517410933244; DSPS: 17095662; Offset : -4318530796
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 537412077924; DSPS: 17751059; Offset : -4318515239
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 557414091508; DSPS: 18406485; Offset : -4318515739
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 577416251086; DSPS: 19061916; Offset : -4318523039
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 597418163369; DSPS: 19717338; Offset : -4318502767
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 617421024873; DSPS: 20372792; Offset : -4318509941
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 637423279761; DSPS: 21028226; Offset : -4318513329
,I/ActivityManager( 1039): Killing 7210:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_7210/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 657425086888; DSPS: 21683645; Offset : -4318506765
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 677427298704; DSPS: 22339078; Offset : -4318522705
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 697429573279; DSPS: 22994512; Offset : -4318506328
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 717432334157; DSPS: 23649963; Offset : -4318522679
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 737434447275; DSPS: 24305392; Offset : -4318515377
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 757436634350; DSPS: 24960824; Offset : -4318525464
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 777438548197; DSPS: 25616246; Offset : -4318503603
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{1d6e9c51 type 0 when 1449681579428 com.google.android.gms} when 1449681579428
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
,I/EventLogService( 2354): Aggregate from 1449679779346 (log), 1449679779346 (data)
,I/art     ( 2125): Explicit concurrent mark sweep GC freed 46613(2MB) AllocSpace objects, 25(3MB) LOS objects, 51% free, 30MB/62MB, paused 1.149ms total 76.438ms
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 797440877929; DSPS: 26271683; Offset : -4318523828
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 817443029223; DSPS: 26927113; Offset : -4318508765
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 837444695362; DSPS: 27582528; Offset : -4318521042
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 857446603895; DSPS: 28237950; Offset : -4318504467
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated(),
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 877448769616; DSPS: 28893381; Offset : -4318505781
,I/[SystemUI]LGPowerUI( 1455): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1455): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1455): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
D/WifiController( 1039): battery changed pluggedType: 2
D/LEDHandler( 1959): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1959): Battery Level Remaining: 100%
D/LEDHandler( 1959): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1455): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1455): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 897451013516; DSPS: 29548815; Offset : -4318519973
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 917453038664; DSPS: 30204241; Offset : -4318509115
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 937455190844; DSPS: 30859672; Offset : -4318523684
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 957457490263; DSPS: 31515107; Offset : -4318513058
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 977459651870; DSPS: 32170538; Offset : -4318518069
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 997461819415; DSPS: 32825969; Offset : -4318517505
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1017464027272; DSPS: 33481401; Offset : -4318506626
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1037465671170; DSPS: 34136815; Offset : -4318510836
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1057467605382; DSPS: 34792239; Offset : -4318529852
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1077469545530; DSPS: 35447662; Offset : -4318512259
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1097472358075; DSPS: 36103114; Offset : -4318507410
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=671771015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8149 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8149): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8149): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2990ca59
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=671771015 [*alarm*], flags=0x0
I/ActivityManager( 1039): Killing 6746:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 7096): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 7096): android.os.DeadObjectException
W/System.err( 7096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7096): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 7096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7096): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7096): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7096): android.os.DeadObjectException
W/System.err( 7096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7096): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 7096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7096): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7096): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 7096): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6746/cgroup.procs: No such file or directory
,W/ActivityManager( 1039): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 7096): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 7096): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1039): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8182 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 7096): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8182): Quickset Services start...
,I/UEI.SmartControl( 8182): Manufacture = LGE
D/UEI.SmartControl( 8182): Id = LGNevo
D/UEI.SmartControl( 8182): File observer start...
E/UEI.SmartControl( 8182): IR Port is disabled: false
D/UEI.SmartControl( 8182): Starting file observer...
D/UEI.SmartControl( 8182): Extracting JNI libs...
D/UEI.SmartControl( 8182): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8182): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8182): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8182): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8182): --- Selecting new region: 6
,I/UEI.SmartControl( 8182): Model = LG-D855
,D/UEI.SmartControl( 8182): QS Service created
I/UEI.SmartControl( 8182): Service initServices...
,D/UEI.SmartControl( 8182): QS start get config
D/UEI.SmartControl( 8182): Loading JNI Libs...
,I/UEI.SmartControl( 8182): Supports setup maps: true
D/UEI.SmartControl( 8182): QS start statue = true Error code = 0
,I/UEI.SmartControl( 8182): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 8182): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 8182): ### init IR Blaster...
D/serial_port( 8182): Configuring serial port
E/UEI.SmartControl( 8182): UEIBLaster setting for 616
I/UEI.SmartControl( 8182): Setting serial record hearder size = 2
I/UEI.SmartControl( 8182): configuring settings for MAXQ616
I/UEI.SmartControl( 8182): Get version...
,D/UEI.SmartControl( 8182): serial port data available: 21
,D/UEI.SmartControl( 8182): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 8182): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8182): QS saving settings...
D/UEI.SmartControl( 8182): IR Blaster version: 25672567
,D/UEI.SmartControl( 8182): serial port data available: 4
,I/UEI.SmartControl( 8182): Device manager: loading config....
,D/UEI.SmartControl( 8182): ----------- loading internal config...
W/ContextImpl( 8182): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 8182): Services init done
D/UEI.SmartControl( 8182): QS Service init finished
D/UEI.SmartControl( 8182): QS Service version name: 2.1.91
D/UEI.SmartControl( 8182): QS Service version code: 201091
D/UEI.SmartControl( 8182): Service requested: Control
E/UEI.SmartControl( 8182): Loading SETTINGS...
D/UEI.SmartControl( 8182): Request IControl service: devices are loaded...
I/QRemote ( 7096): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/ActivityManager( 1039): Killing 7096:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 8182): ------ IControl API: 11
,I/UEI.SmartControl( 8182): Registering callback...
D/UEI.SmartControl( 8182): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8182): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8182): -----service ready thread exits
W/libprocessgroup( 1039): failed to open /acct/uid_10112/pid_7096/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8182): Internal service binding...
D/serial_port( 8182): close(fd = 25)
,D/UEI.SmartControl( 8182): Internal timer expired: 1
D/UEI.SmartControl( 8182): unbind internal service
D/UEI.SmartControl( 8182): Service.onUnbind: IControl
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1117478071921; DSPS: 36758662; Offset : -4318530894
D/UEI.SmartControl( 8182): Service.onDestroy
D/UEI.SmartControl( 8182): Lock is in USE false
D/UEI.SmartControl( 8182): unbind internal service
W/System.err( 8182): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@78931b8
W/System.err( 8182): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8182): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 8182): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8182): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8182): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8182): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8182): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 8182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8182): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8182): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8182): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8182): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8182): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@78931b8
I/UEI.SmartControl( 8182): Serial port is closed.
I/UEI.SmartControl( 8182): Serial port is closed.
I/UEI.SmartControl( 8182): Serial port is closed.
D/UEI.SmartControl( 8182): Blaster closed
D/UEI.SmartControl( 8182): Shut down QS...
D/UEI.SmartControl( 8182): Stopping QS lib
D/UEI.SmartControl( 8182): QS lib stop result = true
,D/UEI.SmartControl( 8182): Stopped QS lib
D/UEI.SmartControl( 8182): Stopped file observer...
D/UEI.SmartControl( 8182): QS shutdown complete
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1137480646393; DSPS: 37414106; Offset : -4318519847
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1157482315188; DSPS: 38069521; Offset : -4318529544
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1177484561586; DSPS: 38724954; Offset : -4318510982
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1197486615015; DSPS: 39380381; Offset : -4318502126
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1217488499175; DSPS: 40035803; Offset : -4318510109
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1237491194219; DSPS: 40691252; Offset : -4318531103
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1257493361243; DSPS: 41346683; Offset : -4318530671
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1277495538944; DSPS: 42002114; Offset : -4318519666
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1297497750081; DSPS: 42657547; Offset : -4318536546
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1317499853251; DSPS: 43312975; Offset : -4318508415
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1337502668244; DSPS: 43968427; Offset : -4318501299
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1357504849642; DSPS: 44623859; Offset : -4318516959
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1377507032655; DSPS: 45279291; Offset : -4318531291
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1397509199731; DSPS: 45934721; Offset : -4318500522
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1417511988578; DSPS: 46590173; Offset : -4318519162
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1437513851226; DSPS: 47245594; Offset : -4318518061
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1457515711687; DSPS: 47901015; Offset : -4318519198
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1477517906262; DSPS: 48556447; Offset : -4318521915
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1497520759329; DSPS: 49211901; Offset : -4318537475
,I/[SystemUI]LGPowerUI( 1455): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1455): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1455): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1455): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
,D/LEDHandler( 1959): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1959): Battery Level Remaining: 100%
D/LEDHandler( 1959): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1455): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1517522650571; DSPS: 49867322; Offset : -4318507752
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1537524559834; DSPS: 50522745; Offset : -4318521278
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1557526779722; DSPS: 51178178; Offset : -4318528863
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1577528863360; DSPS: 51833606; Offset : -4318520653
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1597531517207; DSPS: 52489053; Offset : -4318521887
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1617533684074; DSPS: 53144484; Offset : -4318521742
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1637535296879; DSPS: 53799897; Offset : -4318526291
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1657537572080; DSPS: 54455331; Offset : -4318509469
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1677539474624; DSPS: 55110754; Offset : -4318529584
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1697541697065; DSPS: 55766186; Offset : -4318504331
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1717543346797; DSPS: 56421601; Offset : -4318532962
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1737545370018; DSPS: 57077027; Offset : -4318523953
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1757547543240; DSPS: 57732458; Offset : -4318517531
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1777549429586; DSPS: 58387880; Offset : -4318523249
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1797552265151; DSPS: 59043333; Offset : -4318525818
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1817554263634; DSPS: 59698758; Offset : -4318510927
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1837555890396; DSPS: 60354172; Offset : -4318531958
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1857557975129; DSPS: 61009600; Offset : -4318522603
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1877560135903; DSPS: 61665031; Offset : -4318528602
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
,I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1897562004020; DSPS: 62320452; Offset : -4318522032
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1917564133179; DSPS: 62975882; Offset : -4318529103
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1937566160827; DSPS: 63631308; Offset : -4318515614
,I/[SystemUI]TimeTickManager( 1455): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1455): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1455): called onTimeUpdated()
I/[SystemUI]Clock( 1455): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1957568454569; DSPS: 64286743; Offset : -4318510796
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1977570641802; DSPS: 64942175; Offset : -4318520593
,TIME-OUT KILL (timeout was 1800000ms)
```
