#### Test 5065027881383b1_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1446): called onTimeUpdated()
I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/AndroidRuntime( 7040): 
D/AndroidRuntime( 7040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7040): CheckJNI is OFF
D/AndroidRuntime( 7040): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1948): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{154a831c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{154a831c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  333): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7060 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7040): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1858): Display #0 changed.
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{3eea87d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{31a20372 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7060): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7060): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7060): Loading: webviewchromium
I/LibraryLoader( 7060): Time to load native libraries: 4 ms (timestamps 6583-6587)
,I/LibraryLoader( 7060): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7060): Binding Chromium to main looper Looper (main, tid 1) {25764384}
,I/LibraryLoader( 7060): Expected native library version number "",actual native library version number ""
I/chromium( 7060): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7060): Initializing chromium process, renderers=0
,W/art     ( 7060): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb1427180, uid 10311
,W/chromium( 7060): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7060): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7060): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a3726c6:true
I/Adreno-EGL( 7060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7060): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7060): Build Date: 12/12/14 금
I/Adreno-EGL( 7060): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7060): Remote Branch: 
I/Adreno-EGL( 7060): Local Patches: 
I/Adreno-EGL( 7060): Reconstruct Branch: 
,W/chromium( 7060): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7060): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7060): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7060): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7060): CordovaWebView is running on device made by: LGE
,W/art     ( 7060): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7060): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7060): Render dirty regions requested: true
I/OpenGLRenderer( 7060): Initialized EGL, version 1.4
D/OpenGLRenderer( 7060): Enabling debug mode 0
,D/Atlas   ( 7060): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{32be0e50 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7060): LgDataFeature() Constructor: none
,D/LgDataFeature( 7060): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@a9dcade,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1446): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1446): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1446):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1446): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 7060): Timeline: Activity_idle id: android.os.BinderProxy@a3395b4 time:286987
,I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +581ms (total +665ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{8548b25 u0 com.test.thalitest/.MainActivity t4} time:286991
D/JsMessageQueue( 7060): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7060): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435069184
D/JX-Cordova( 7060): jxcore cordova android initializing
,E/GBMv2   (  333): DFP En is all cleared set to be enabled
E/GBMv2   (  333): Set value is all cleared set the max
I/GBMv2   (  333): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7060): Initializing JXcore engine
,W/jxcore-log( 7060): JXcore engine is ready
W/jxcore-log( 7060): Starting JXcore engine
W/.test.thalitest( 7060): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7315]" dev="sockfs" ino=7315 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7060): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 7060): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10589]" dev="sockfs" ino=10589 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7060): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/.test.thalitest( 7060): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[31706]" dev="sockfs" ino=31706 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7060): Platform android
W/jxcore-log( 7060): 
W/jxcore-log( 7060): Process ARCH arm
W/jxcore-log( 7060): 
,I/jxcore-log( 7060): JXcore Cordova bridge is ready!
I/jxcore-log( 7060): 
W/jxcore-log( 7060): JXcore engine is started
,I/jxcore-log( 7060): Toggling radios to true
I/jxcore-log( 7060): 
,D/BluetoothAdapter( 7060): enable(): BT is already enabled..!
D/WifiService( 1031): New client listening to asynchronous messages
D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=7060, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=7060, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1031): disconnect pid=7060, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1031):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1031): [290,466,422 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1031): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1031): reconnect pid=7060, uid=10311, packageName=com.test.thalitest
,I/jxcore-log( 7060): Radios toggled
I/jxcore-log( 7060): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7060): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7060): 
I/jxcore-log( 7060): Perf Test app loaded loaded
I/jxcore-log( 7060): 
I/jxcore-log( 7060): check test folder
I/jxcore-log( 7060): 
I/jxcore-log( 7060): found test : ./testFindPeers.js
I/jxcore-log( 7060): 
,I/jxcore-log( 7060): found test : ./testSendData.js
I/jxcore-log( 7060): 
,I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1031): DISCONNECT: returned true
E/WifiStateMachine( 1031): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1031): InitialState.processMessage what=4
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1031): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1031): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/CommandListener(  311): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1031): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2135): Read error: ssl=0xaa6d9c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaa6d9c00: I/O error during system call, Broken pipe
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7115 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiHS20( 1031): hidePasspointNotification off =false
D/ConnectivityService( 1031): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1948): handleWifiStateChangedEvent: 0
,E/WifiStateMachine( 1031): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1031):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1031): [290,616,433 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1031): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1031): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1031): disableDataServiceNotify
D/DSQN    ( 1031): stop dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiNative-wlan0( 1031): RECONNECT: returned true
E/WifiStateMachine( 1031):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290647
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290647
D/LGWifiP2pService( 1031): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/CommandListener(  311): Clearing all IP addresses on wlan0
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=290657  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1031): hidePasspointNotification off =false
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=290658  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524292
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Da,ta not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1031): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Disconnected - quitting
D/CSLegacyTypeTracker( 1031): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1031): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1031): Removing idletimer
W/Settings( 1031): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1031): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1031): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1031): NetworkAgent: NetworkAgent channel lost
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=290668  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 103,1): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=290670  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1031): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1031): hidePasspointNotification off =false
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/chromium( 7060): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
I/chromium( 7060): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7060): 
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7115): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7115): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7115): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7115): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7115): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7115): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7060): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1031): StoppedState
D/DhcpStateMachine( 1031): StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7115): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7115): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7115): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7115): [AUTORUN] getUsbConnected() : connected=true
I/chromium( 7060): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7060): 
,D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7115): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7115): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7152 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6728:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_6728/cgroup.procs: No such file or directory
,I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7115): LgDataFeature() Constructor: none
,D/LgDataFeature( 7115): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
I/ActivityManager( 1031): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7177 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1031): Killing 6167:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6167/cgroup.procs: No such file or directory
,W/ResourcesManager( 7177): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7177): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7177): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7177): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7177): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7177): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7177): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7177): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7177): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7177): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7177): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
,D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7177): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7177): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7177): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7177): LgDataFeature() Constructor: none
D/LgDataFeature( 7177): LgDataFeature() Constructor Done, null
,V/SoundPool( 7177): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7177): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7177): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7177): doLoad: loading sample sampleID=1
I/QRemote ( 7177): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7177): Start decode
V/MediaPlayer[Native]( 7177): decode(31, 10857164, 17813)
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
D/UEI.SmartControl( 6786): QS Service created
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb5474840, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
,D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/QRemote ( 7177): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7177): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6786): Service initServices...
D/UEI.SmartControl( 6786): QS start get config
V/LGMDMManager( 7177): Create singleton instance
,V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c33d0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3600 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3650 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb5474840, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb5474840, 1, 0, 0)
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
V/OM,XCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815824
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816304
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816384
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816464
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3600 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb57c33d0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb5474840, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab602000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab603000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab604000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab605000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab606000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab607000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab608000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab609000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60a000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60b000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60c000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60d000, 0xb57da000, 4096)
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60e000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab60f000, 0xb57da000, 4096)
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab610000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab611000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab612000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab613000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab614000, 0xb57da000, 4096)
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8320
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab615000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab616000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab617000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab618000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab619000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61a000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61b000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61c000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61d000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61e000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab61f000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab620000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab621000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab622000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab623000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab624000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab625000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab626000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab627000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab628000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab629000, 0xb57da000, 4096)
,V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62a000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62b000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62c000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62d000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62e000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab62f000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab630000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab631000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab632000, 0xb57da000, 4096)
V/AudioCache(  316): write(0xb57da000, 4096)
V/AudioCache(  316): memcpy(0xab633000, 0xb57da000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57da000, 280)
V/AudioCache(  316): memcpy(0xab634000, 0xb57da000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb5474840, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb5474840, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): Pause Playback at 1068125
V/AudioCache(  316): wait - success
,V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb5474840, 8, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb57c33d0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb57c35b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3600 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7177): close(31)
V/SoundPool( 7177): pointer = 0x9fe4a000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6786): Supports setup maps: true
D/UEI.SmartControl( 6786): QS start statue = true Error code = 0
I/UEI.SmartControl( 6786): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6786): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6786): ### init IR Blaster...
D/serial_port( 6786): Configuring serial port
,E/UEI.SmartControl( 6786): UEIBLaster setting for 616
I/UEI.SmartControl( 6786): Setting serial record hearder size = 2
I/UEI.SmartControl( 6786): configuring settings for MAXQ616
I/UEI.SmartControl( 6786): Get version...
D/UEI.SmartControl( 6786): serial port data available: 21
,D/UEI.SmartControl( 6786): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6786): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6786): QS saving settings...
,D/UEI.SmartControl( 6786): IR Blaster version: 25672567
D/UEI.SmartControl( 6786): serial port data available: 4
,W/ContextImpl( 6786): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6786): Device manager: loading config....
D/UEI.SmartControl( 6786): ----------- loading internal config...
E/UEI.SmartControl( 6786): Services init done
D/UEI.SmartControl( 6786): QS Service init finished
D/UEI.SmartControl( 6786): QS Service version name: 2.1.91
D/UEI.SmartControl( 6786): QS Service version code: 201091
D/UEI.SmartControl( 6786): Service requested: Control
D/UEI.SmartControl( 6786): Request IControl service: devices are loaded...
,E/UEI.SmartControl( 6786): Loading SETTINGS...
I/QRemote ( 7177): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6786): ------ IControl API: 11
D/UEI.SmartControl( 6786): File observer start...
E/UEI.SmartControl( 6786): IR Port is disabled: false
D/UEI.SmartControl( 6786): Starting file observer...
I/UEI.SmartControl( 6786): Registering callback...
,I/UEI.SmartControl( 6786): ------ IControl API: 19
I/UEI.SmartControl( 6786): Registering Services Ready callback...
D/UEI.SmartControl( 6786): Internal service binding...
D/UEI.SmartControl( 6786): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6786): Notify AllClients services are ready: 0
,I/QRemote ( 7177): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7177): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7177): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7177): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/UEI.SmartControl( 6786): -----service ready thread exits
D/QRemote ( 7177): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6786): ------ IControl API: 8
D/QRemote ( 7177): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7177): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7177): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7177): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7177): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7177): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7177): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7177): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7177): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7177): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449753132399]
D/QRemote ( 7177): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1031): Killing 6190:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7177): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_6190/cgroup.procs: No such file or directory
V/QRemote ( 7177): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7177): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2667): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=292790  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=292824  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7177): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
I/wpa_supplicant( 2667): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 2667): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292910  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292917  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292918
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292918
E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292918
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292919
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292920
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292940  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292955  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292955  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292957  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292958
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292958
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7115): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7115): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7115): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
D/UsbSettingsControl( 7115): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7115): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7115): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7115): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1031): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1031): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293018  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293019  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293020  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1031):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1031):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293025  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293025  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293026  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2405af84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2405af84 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
,D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1031): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1031): ignoring duplicate network state non-change
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1031): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1948): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1031): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 101
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
,D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1031): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1858): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMME,DIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
,D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
W/dsqn    ( 7248): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7248): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
,V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/DSQN    ( 7248): DSQN ssw
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7177): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7177): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7177): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7177): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7115): MCCMNC not supported: null
D/QRemote ( 7177): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7177): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7177): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7177): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7177): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
,D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1031): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:12:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449753133463], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449753133443]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Validated
D/ConnectivityService( 1031): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1858): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1031): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7254): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7254): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7254): version 5.5.6 starting
E/dhcpcd  ( 7254): get_duid: m
D/dhcpcd  ( 7254): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7254): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7254): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7254): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7254): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7254): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 7254): wlan0: sending REQUEST (xid 0x372a4046), next in 3.72 seconds
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=122186540, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2646abdc type 2 when 293612 android} when 293612
D/[Concierge]Service( 2589): onStartCommand(). Type : 9
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5940): type=WIFI subType= reason=null isConnected=true
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=122186540 [*alarm*], flags=0x0
,I/NetworkMonitor( 5940): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/BooksSync( 6544): Starting books sync
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7291 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7291): onCreate
W/AppUp4:DB( 7291):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7291):  setFingerPrint start
,I/AppUp4:DB( 7291):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7291):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7291):  SDK version = 21
I/AppUp4:DB( 7291):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7291): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7291): onReceive
I/art     ( 1031): Explicit concurrent mark sweep GC freed 88804(4MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.656ms total 119.828ms
,D/BooksSync( 6544): started syncMyEbooks
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LgDataFeature( 7291): LgDataFeature() Constructor: none
,D/LgDataFeature( 7291): LgDataFeature() Constructor Done, null
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7291): Context : android.app.ReceiverRestrictedContext@17832fa2
D/AppUp4:CustFacade( 7291): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7291): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7291): begin check event
I/AppUp4:CustModeStarterReceiver( 7291): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7291): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7291): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7291): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7291): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3380): DownloadService onCreate
I/LGDMClient( 4340): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3380): in removeSpuriousFiles
D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4340): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4340): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4340): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@3233fe14 on behalf of 3380
V/DownloadManager( 3380): DownloadService onStartCommand
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@22af54b2 on behalf of 3380
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3380): processing inserted download 1
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3380): in trimDatabase
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6544): Authentication error
E/BooksAccountManager( 6544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6544): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6544): null auth token
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@24217c03 on behalf of 3380
V/DownloadManager( 3380): processing inserted download 4
V/DownloadManager( 3380): processing inserted download 7
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
V/DownloadManager( 3380): processing inserted download 8
V/DownloadManager( 3380): processing inserted download 9
V/DownloadManager( 3380): processing inserted download 10
V/DownloadManager( 3380): processing inserted download 16
V/DownloadManager( 3380): processing inserted download 17
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3380): processing inserted download 18
,V/DownloadManager( 3380): processing inserted download 21
V/DownloadManager( 3380): DownloadService onDestroy
D/eas_req ( 6753): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
W/ResourcesManager( 1397): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1397): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7320 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 21.426ms
,I/HubEmail( 6753): JNI_OnLoad()
I/HubEmail( 6753): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6753): registerNatives()
I/HubEmail( 6753): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNativeMethods()
I/HubEmail( 6753): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.639ms
W/art     ( 6753): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 376us total 16.661ms
I/LgeMiscReceiver( 3351): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3351): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3351): networkInfo.isConnected() = false
,I/ActivityManager( 1031): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7343 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,E/WifiStateMachine( 1031):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1031): identical MTU - not setting
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524295
I/dhcpcd  ( 7254): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,W/ApiaryClient( 6544): Error response from books API: {
W/ApiaryClient( 6544):  "error": {
W/ApiaryClient( 6544):   "errors": [
W/ApiaryClient( 6544):    {
W/ApiaryClient( 6544):     "domain": "global",
W/ApiaryClient( 6544):     "reason": "required",
W/ApiaryClient( 6544):     "message": "Login Required",
W/ApiaryClient( 6544):     "locationType": "header",
W/ApiaryClient( 6544):     "location": "Authorization"
W/ApiaryClient( 6544):    }
W/ApiaryClient( 6544):   ],
W/ApiaryClient( 6544):   "code": 401,
W/ApiaryClient( 6544):   "message": "Login Required"
W/ApiaryClient( 6544):  }
W/ApiaryClient( 6544): }
,W/ApiaryClient( 6544): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6544): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8150388392497238145&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6544): Headers:
W/ApiaryClient( 6544): accept-encoding: [gzip]
W/ApiaryClient( 6544): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6544): gdata-version: 2
I/dhcpcd  ( 7254): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 7254): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 7254): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7254): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7254): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7254): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7254): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7254): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7369 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6639:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_6639/cgroup.procs: No such file or directory
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7400 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6216:com.android.gallery3d/u0a27 (adj 15): empty #17
,V/FormManager( 7320): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7320): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6216/cgroup.procs: No such file or directory
I/ActivityManager( 1031): Killing 6236:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     ( 7400): Almond Protected OAT
,D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1031): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1031): RunningState
W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_6236/cgroup.procs: No such file or directory
,D/WeatherApplication( 7400): removeAccount
D/WeatherApplication( 7400): Account.length = 0
E/WeatherApplication( 7400): OPERATOR:OPEN
D/WeatherAncestor( 7400): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:15
D/Weather.Utils( 7400): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7400): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7400): 2 : This is isUpdating : false
,D/WeatherAncestor( 7400): connectivity changed - connection : true
D/WeatherService( 7400): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7400): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7400): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7400): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7400): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7400): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:15
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7422 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6807:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_6807/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7422): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/jxcore-log( 7060): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7060): 
I/LibraryLoader( 7422): Loading: webviewchromium
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 7422): Time to load native libraries: 5 ms (timestamps 5499-5504)
I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7422): Binding Chromium to main looper Looper (main, tid 1) {3786d395}
,I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
,I/chromium( 7422): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/BrowserStartupController( 7422): Initializing chromium process, renderers=0
,W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 7422): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7422): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7422): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6544): Authentication error
E/BooksAccountManager( 6544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6544): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6544): null auth token
I/Adreno-EGL( 7422): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7422): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7422): Build Date: 12/12/14 금
I/Adreno-EGL( 7422): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7422): Remote Branch: 
I/Adreno-EGL( 7422): Local Patches: 
I/Adreno-EGL( 7422): Reconstruct Branch: 
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
V/AudioPolicyService(  316): registerClient() client 0xb558a940, uid 10093
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
W/AudioManagerAndroid( 7422): Requires BLUETOOTH permission
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1031):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/ApiaryClient( 6544): Error response from books API: {
W/ApiaryClient( 6544):  "error": {
W/ApiaryClient( 6544):   "errors": [
W/ApiaryClient( 6544):    {
W/ApiaryClient( 6544):     "domain": "global",
W/ApiaryClient( 6544):     "reason": "required",
W/ApiaryClient( 6544):     "message": "Login Required",
W/ApiaryClient( 6544):     "locationType": "header",
W/ApiaryClient( 6544):     "location": "Authorization"
W/ApiaryClient( 6544):    }
W/ApiaryClient( 6544):   ],
W/ApiaryClient( 6544):   "code": 401,
W/ApiaryClient( 6544):   "message": "Login Required"
W/ApiaryClient( 6544):  }
W/ApiaryClient( 6544): }
,W/ApiaryClient( 6544): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6544): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8150388392497238145&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6544): Headers:
W/ApiaryClient( 6544): accept-encoding: [gzip]
W/ApiaryClient( 6544): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6544): gdata-version: 2
I/NSApplication( 7422): Starting up...
,I/ActivityManager( 1031): Killing 6847:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6847/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7291): onReceive
D/AppUp4:CustFacade( 7291): Context : android.app.ReceiverRestrictedContext@17832fa2
D/AppUp4:CustFacade( 7291): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7291): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7291): begin check event
,I/AppUp4:CustModeStarterReceiver( 7291): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3380): DownloadService onCreate
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LGDMClient( 4340): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3380): in removeSpuriousFiles
,V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@173a09fe on behalf of 3380
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3380): DownloadService onStartCommand
V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3380): in trimDatabase
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@1368fbac on behalf of 3380
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@1369c075 on behalf of 3380
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3380): processing inserted download 1
V/DownloadManager( 3380): processing inserted download 4
E/LGDMClient( 4340): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4340): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4340): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3380): processing inserted download 7
,I/LgeMiscReceiver( 3351): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3351): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3351): networkInfo.isConnected() = false
V/DownloadManager( 3380): processing inserted download 8
V/DownloadManager( 3380): processing inserted download 9
W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3380): processing inserted download 10
V/DownloadManager( 3380): processing inserted download 16
V/DownloadManager( 3380): processing inserted download 17
V/DownloadManager( 3380): processing inserted download 18
V/DownloadManager( 3380): processing inserted download 21
D/WeatherAncestor( 7400): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:16
,V/DownloadManager( 3380): DownloadService onDestroy
,D/Weather.Utils( 7400): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7400): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7400): 2 : This is isUpdating : false
D/WeatherAncestor( 7400): connectivity changed - connection : true
D/WeatherService( 7400): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@bd613f0
D/ForecastDataCache( 7400): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7400): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7400): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7400): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7400): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:16
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
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
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
V/FormManager( 7320): There are no updated forms. The schedule will be deleted.
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
V/FormManager( 7320): Alarm would be updated, because LastCheckTime has been updated.
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
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
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6699): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5940): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7291): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7291): onReceive
D/AppUp4:CustFacade( 7291): Context : android.app.ReceiverRestrictedContext@17832fa2
D/AppUp4:CustFacade( 7291): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7291): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7291): begin check event
I/AppUp4:CustModeStarterReceiver( 7291): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3380): DownloadService onCreate
I/DownloadManager( 3380): in removeSpuriousFiles
I/LGDMClient( 4340): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4340): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@1c0c687b on behalf of 3380
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
,I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3380): DownloadService onStartCommand
V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3380): in trimDatabase
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@1c935ad6 on behalf of 3380
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@27ef1157 on behalf of 3380
V/DownloadManager( 3380): processing inserted download 1
,V/DownloadManager( 3380): processing inserted download 4
E/LGDMClient( 4340): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4340): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4340): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3380): processing inserted download 7
V/DownloadManager( 3380): processing inserted download 8
V/DownloadManager( 3380): processing inserted download 9
W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3380): processing inserted download 10
V/DownloadManager( 3380): processing inserted download 16
V/DownloadManager( 3380): processing inserted download 17
,V/DownloadManager( 3380): processing inserted download 18
,W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3380): processing inserted download 21
I/LgeMiscReceiver( 3351): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3351): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3351): networkInfo.isConnected() = true
D/PhoneState( 3351): setPdpRejectCasuse : false
V/DownloadManager( 3380): DownloadService onDestroy
,D/WeatherAncestor( 7400): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:16
,D/Weather.Utils( 7400): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7400): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7400): 2 : This is isUpdating : false
D/WeatherAncestor( 7400): connectivity changed - connection : true
D/WeatherService( 7400): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@bd613f0
D/ForecastDataCache( 7400): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7400): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7400): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7400): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7400): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:12:16
V/FormManager( 7320): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7320): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2354): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
,D/QuickCircle( 1397): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 43134(2MB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.197ms total 65.568ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6544): Authentication error
E/BooksAccountManager( 6544): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6544): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6544): null auth token
,W/ApiaryClient( 6544): Error response from books API: {
W/ApiaryClient( 6544):  "error": {
W/ApiaryClient( 6544):   "errors": [
W/ApiaryClient( 6544):    {
W/ApiaryClient( 6544):     "domain": "global",
W/ApiaryClient( 6544):     "reason": "required",
W/ApiaryClient( 6544):     "message": "Login Required",
W/ApiaryClient( 6544):     "locationType": "header",
W/ApiaryClient( 6544):     "location": "Authorization"
W/ApiaryClient( 6544):    }
W/ApiaryClient( 6544):   ],
W/ApiaryClient( 6544):   "code": 401,
W/ApiaryClient( 6544):   "message": "Login Required"
W/ApiaryClient( 6544):  }
W/ApiaryClient( 6544): }
W/ApiaryClient( 6544): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6544): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8150388392497238145&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6544): Headers:
W/ApiaryClient( 6544): accept-encoding: [gzip]
W/ApiaryClient( 6544): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6544): gdata-version: 2
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 26065(1205KB) AllocSpace objects, 6(864KB) LOS objects, 33% free, 44MB/66MB, paused 2.559ms total 148.604ms
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/UEI.SmartControl( 6786): Internal timer expired: 2
D/UEI.SmartControl( 6786): unbind internal service
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{c28c80a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
D/serial_port( 6786): close(fd = 24)
I/UEI.SmartControl( 6786): Serial port is closed.
,D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1c71993a type 2 when 297530 com.google.android.gms} when 297530
,V/QRemote ( 7177): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
D/QRemote ( 7177): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8320
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
,D/GCM     ( 2135): Connected
,W/Uploader( 2135): No account for auth token provided
D/GCM     ( 2135): Message class com.google.f.a.a.p
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,E/BooksSync( 6544): Soft error: 
E/BooksSync( 6544): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6544): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8150388392497238145&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6544): Headers:
E/BooksSync( 6544): accept-encoding: [gzip]
E/BooksSync( 6544): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6544): gdata-version: 2
E/BooksSync( 6544): 
E/BooksSync( 6544): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6544): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6544): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6544): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6544): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6544): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6544): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6544): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6544): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6544): {
E/BooksSync( 6544):  "error": {
E/BooksSync( 6544):   "errors": [
E/BooksSync( 6544):    {
E/BooksSync( 6544):     "domain": "global",
E/BooksSync( 6544):     "reason": "required",
E/BooksSync( 6544):     "message": "Login Required",
E/BooksSync( 6544):     "locationType": "header",
E/BooksSync( 6544):     "location": "Authorization"
E/BooksSync( 6544):    }
E/BooksSync( 6544):   ],
E/BooksSync( 6544):   "code": 401,
E/BooksSync( 6544):   "message": "Login Required"
E/BooksSync( 6544):  }
E/BooksSync( 6544): }
E/BooksSync( 6544): 
E/BooksSync( 6544): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6544): 	... 8 more
,E/BooksSync( 6544): Sync error
E/BooksSync( 6544): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6544): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8150388392497238145&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6544): Headers:
E/BooksSync( 6544): accept-encoding: [gzip]
E/BooksSync( 6544): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6544): gdata-version: 2
E/BooksSync( 6544): 
E/BooksSync( 6544): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6544): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6544): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6544): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6544): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6544): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6544): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6544): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6544): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6544): {
E/BooksSync( 6544):  "error": {
E/BooksSync( 6544):   "errors": [
E/BooksSync( 6544):    {
E/BooksSync( 6544):     "domain": "global",
E/BooksSync( 6544):     "reason": "required",
E/BooksSync( 6544):     "message": "Login Required",
E/BooksSync( 6544):     "locationType": "header",
E/BooksSync( 6544):     "location": "Authorization"
E/BooksSync( 6544):    }
E/BooksSync( 6544):   ],
E/BooksSync( 6544):   "code": 401,
E/BooksSync( 6544):   "message": "Login Required"
E/BooksSync( 6544):  }
E/BooksSync( 6544): }
E/BooksSync( 6544): 
E/BooksSync( 6544): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6544): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6544): 	... 8 more
I/BooksSync( 6544): Finished books sync
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 298041378692; DSPS: 9907317; Offset : -4322586705
,I/ActivityManager( 1031): Killing 6864:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293612, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6864/cgroup.procs: No such file or directory
,W/Uploader( 2135): No account for auth token provided
,W/Uploader( 2135): No account for auth token provided
,W/Uploader( 2135): No account for auth token provided
,W/Uploader( 2135):  no longer exists, so no auth token.
,I/GAV4    ( 7422): Thread[GAThread,5,main]: No campaign data found.

```
