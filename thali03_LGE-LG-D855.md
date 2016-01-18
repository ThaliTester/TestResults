#### Test 56151093f6e24ff_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1471): called onTimeUpdated()
I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
,D/AndroidRuntime( 7139): 
D/AndroidRuntime( 7139): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7139): CheckJNI is OFF
D/AndroidRuntime( 7139): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1934): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{2c60e9e5 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{2c60e9e5 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7158 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7139): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1845): Display #0 changed.
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{1420a302 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{191c3413 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7158): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7158): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7158): Loading: webviewchromium
I/LibraryLoader( 7158): Time to load native libraries: 2 ms (timestamps 9047-9049)
I/LibraryLoader( 7158): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7158): Binding Chromium to main looper Looper (main, tid 1) {1974b332}
I/LibraryLoader( 7158): Expected native library version number "",actual native library version number ""
I/chromium( 7158): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7158): Initializing chromium process, renderers=0
,W/art     ( 7158): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  323): registerClient() client 0xb14fd8a0, uid 10311
,W/chromium( 7158): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7158): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7158): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bab6f47:true
I/Adreno-EGL( 7158): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7158): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7158): Build Date: 12/12/14 금
I/Adreno-EGL( 7158): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7158): Remote Branch: 
I/Adreno-EGL( 7158): Local Patches: 
I/Adreno-EGL( 7158): Reconstruct Branch: 
,W/chromium( 7158): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7158): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7158): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7158): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7158): CordovaWebView is running on device made by: LGE
,W/art     ( 7158): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7158): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7158): Render dirty regions requested: true
I/OpenGLRenderer( 7158): Initialized EGL, version 1.4
D/OpenGLRenderer( 7158): Enabling debug mode 0
,D/Atlas   ( 7158): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{2ab8fb09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{38a58cba u0 com.test.thalitest/.MainActivity t4}
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1471): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15cfb02f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7158): LgDataFeature() Constructor: none
D/LgDataFeature( 7158): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +604ms (total +702ms)
,I/Timeline( 7158): Timeline: Activity_idle id: android.os.BinderProxy@1f5c4ce2 time:289477
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{38a58cba u0 com.test.thalitest/.MainActivity t4} time:289479
D/JsMessageQueue( 7158): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7158): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434859776
D/JX-Cordova( 7158): jxcore cordova android initializing
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7158): Initializing JXcore engine
W/jxcore-log( 7158): JXcore engine is ready
,W/jxcore-log( 7158): Starting JXcore engine
,W/.test.thalitest( 7158): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10372]" dev="sockfs" ino=10372 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7158): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7158): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7672]" dev="sockfs" ino=7672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7158): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7158): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33364]" dev="sockfs" ino=33364 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7158): Platform android
W/jxcore-log( 7158): 
W/jxcore-log( 7158): Process ARCH arm
W/jxcore-log( 7158): 
,I/jxcore-log( 7158): JXcore Cordova bridge is ready!
I/jxcore-log( 7158): 
W/jxcore-log( 7158): JXcore engine is started
,I/jxcore-log( 7158): Toggling radios to true
I/jxcore-log( 7158): 
,D/BluetoothAdapter( 7158): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7158, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7158, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7158, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=7158, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7158): Radios toggled
I/jxcore-log( 7158): 
I/jxcore-log( 7158): My device name is: LGE-LG-D855
I/jxcore-log( 7158): 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [292,152,200 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/wpa_supplicant( 2686): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7246 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  316): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2062): Read error: ssl=0xaf4d4e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2062): SSL shutdown failed: ssl=0xaf4d4e00: I/O error during system call, Broken pipe
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
,V/WfdStateTracker( 1934): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [292,311,250 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2686): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=292326
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=292326
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/CommandListener(  316): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292364  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1037): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292364  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292367  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292380  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1845): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
W/ResourcesManager( 7246): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7246): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-122ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7246): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7246): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7246): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7246): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7246): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7246): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7283 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6646:com.android.gallery3d/u0a27 (adj 15): empty #17
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 587us total 26.800ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 20.354ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 17.055ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6646/cgroup.procs: No such file or directory
,I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7283): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7246): LgDataFeature() Constructor: none
D/LgDataFeature( 7246): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7304 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6675:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6675/cgroup.procs: No such file or directory
,W/ResourcesManager( 7304): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7304): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 7304): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7304): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7304): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7304): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7304): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7304): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7304): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7283): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7304): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7283): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7283): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7304): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7304): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7304): LgDataFeature() Constructor: none
D/LgDataFeature( 7304): LgDataFeature() Constructor Done, null
V/SoundPool( 7304): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7304): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7304): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7304): doLoad: loading sample sampleID=1
I/QRemote ( 7304): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7304): Start decode
V/MediaPlayer[Native]( 7304): decode(31, 10857164, 17813)
V/MediaPlayerService(  323): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  323): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  323): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  323): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  323): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  323): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  323): player type = 3
V/AwesomePlayer(  323): AwesomePlayer create()
V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/AwesomePlayer(  323): setAudioSink() 
V/AwesomePlayer(  323): reset_l() 
V/AudioCache(  323): notify(0xb54746c0, 8, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
D/UEI.SmartControl( 6760): QS Service created
D/Utils   (  323): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  323): setDataSource_l dataSource
V/LGParserOSAL(  323): SniffLGParser start
V/LGParserOSAL(  323): MainType:5, SubType=0
V/LGParserOSAL(  323): #### check Mime : application/ogg
V/LGParserOSAL(  323): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  323): Use LGExtractor :application/ogg 
D/QRemote ( 7304): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/UEI.SmartControl( 6760): Service initServices...
D/UEI.SmartControl( 6760): QS start get config
V/LGParserOSAL(  323): supported mime: application/ogg
V/AwesomePlayer(  323): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  323): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  323): mBitrate = -1 bits/sec
V/AwesomePlayer(  323): AudioTrack Setting
V/AwesomePlayer(  323): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  323): setAudioSource() 
V/MediaPlayerService(  323): prepare
V/AwesomePlayer(  323): prepareAsync_l() 
V/MediaPlayerService(  323): wait for prepare
V/AwesomePlayer(  323): onPrepareAsyncEvent() 
V/AwesomePlayer(  323): initAudioDecoder() 
W/Utils   (  323): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  323): isOffloadSupported()
V/AudioPolicyManager(  323): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  323): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  323): isAudioPlaybackHookOn() false
V/AwesomePlayer(  323): getUseOffload() = 0 
V/OMXCodec(  323): OMXCodec::Create
V/OMXCodec(  323): findMatchingCodecs()
V/OMXCodec(  323): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  323): matchingCodecs.size()=1
V/OMXCodec(  323): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/QRemote ( 7304): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/OMXCodec(  323): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  323): LG Codec Adapter start
V/OMXCodec(  323): OMXCodec Createtor
V/OMXCodec(  323): setComponentRole
V/OMXCodec(  323): configureCodec protected=0
V/LGCodecAdapter(  323): called getLGCodecSpecificData
V/LGCodecOSAL(  323): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  323): Called LGconfigureCodecMETA
V/LGCodecOSAL(  323): Called LGconfigureCodecMSG
V/LGCodecOSAL(  323): Not support LGCodec
V/OMXCodec(  323): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  323): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  323): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  323): Could not offload audio decode, try pcm offload
W/Utils   (  323): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  323): isOffloadSupported()
V/AudioPolicyManager(  323): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  323): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  323): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  323): init()
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  323): allocateBuffers
V/OMXCodec(  323): allocateBuffersOnPort portIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  323): allocateBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf10 on output port
V/OMXCodec(  323): init() mAsyncCompletion wait!!! 
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  323): init() mAsyncCompletion wait!!! 
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  323): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  323): finishAsyncPrepare_l() 
V/AudioCache(  323): notify(0xb54746c0, 5, 0, 0)
V/AudioCache(  323): ignored
V/AudioCache(  323): notify(0xb54746c0, 1, 0, 0)
V/AudioCache(  323): prepared
V/AudioCache(  323): wait - success
V/MediaPlayerService(  323): start
V/AwesomePlayer(  323): play_l() 
V/AwesomePlayer(  323): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  323): createAudioPlayer_l
V/AwesomePlayer(  323): seekAudioIfNecessary_l() 
V/AwesomePlayer(  323): startAudioPlayer_l() 
D/AudioPlayer(  323): start of Playback, useOffload 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  323): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  323): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  323): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796224
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796464
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797584
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  323): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  323): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  323): allocateBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  323): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  323): notify(0xb54746c0, 6, 0, 0)
V/AudioCache(  323): ignored
V/MediaPlayerService(  323): wait for playback complete
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab602000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab603000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab604000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab605000, 0xb57e9000, 4096)
V/LGMDMManager( 7304): Create singleton instance
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab606000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab607000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab608000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab609000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60a000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60b000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60c000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60d000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60e000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab60f000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab610000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab611000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab612000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab613000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab614000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab615000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab616000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab617000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab618000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab619000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61a000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61b000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61c000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61d000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61e000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab61f000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab620000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab621000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab622000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab623000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab624000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab625000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab626000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab627000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab628000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab629000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62a000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62b000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62c000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62d000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62e000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab62f000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab630000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab631000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab632000, 0xb57e9000, 4096)
V/AudioCache(  323): write(0xb57e9000, 4096)
V/AudioCache(  323): memcpy(0xab633000, 0xb57e9000, 4096)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  323): postAudioEOS() 
V/AudioCache(  323): write(0xb57e9000, 280)
V/AudioCache(  323): memcpy(0xab634000, 0xb57e9000, 280)
V/AwesomePlayer(  323): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  323): onStreamDone
V/AwesomePlayer(  323): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  323): notify(0xb54746c0, 2, 0, 0)
V/AudioCache(  323): playback complete
V/AwesomePlayer(  323): pause_l() 
V/AudioCache(  323): notify(0xb54746c0, 7, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
V/AudioCache(  323): wait - success
V/MediaPlayerService(  323): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  323): Pause Playback at 1068125
V/AwesomePlayer(  323): reset_l() 
V/AudioCache(  323): notify(0xb54746c0, 8, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
D/AudioPlayer(  323): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca60 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcab0 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  323): AudioPlayer releasing audio source
D/AudioPlayer(  323): AudioPlayer done releasing audio source
V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/AwesomePlayer(  323): ~AwesomePlayer call
V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/SoundPool( 7304): close(31)
V/SoundPool( 7304): pointer = 0x9ffee000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1753
I/UEI.SmartControl( 6760): Supports setup maps: true
D/UEI.SmartControl( 6760): QS start statue = true Error code = 0
I/UEI.SmartControl( 6760): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6760): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6760): ### init IR Blaster...
D/serial_port( 6760): Configuring serial port
E/UEI.SmartControl( 6760): UEIBLaster setting for 616
I/UEI.SmartControl( 6760): Setting serial record hearder size = 2
I/UEI.SmartControl( 6760): configuring settings for MAXQ616
I/UEI.SmartControl( 6760): Get version...
D/UEI.SmartControl( 6760): serial port data available: 21
D/UEI.SmartControl( 6760): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6760): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6760): QS saving settings...
D/UEI.SmartControl( 6760): IR Blaster version: 25672567
D/UEI.SmartControl( 6760): serial port data available: 4
I/UEI.SmartControl( 6760): Device manager: loading config....
D/UEI.SmartControl( 6760): ----------- loading internal config...
W/ContextImpl( 6760): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6760): Services init done
D/UEI.SmartControl( 6760): QS Service init finished
D/UEI.SmartControl( 6760): QS Service version name: 2.1.91
D/UEI.SmartControl( 6760): QS Service version code: 201091
D/UEI.SmartControl( 6760): Service requested: Control
E/UEI.SmartControl( 6760): Loading SETTINGS...
D/UEI.SmartControl( 6760): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6760): Request IControl service: devices are loaded...
I/QRemote ( 7304): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6760): Internal service binding...
I/UEI.SmartControl( 6760): ------ IControl API: 11
D/UEI.SmartControl( 6760): File observer start...
E/UEI.SmartControl( 6760): IR Port is disabled: false
D/UEI.SmartControl( 6760): Starting file observer...
I/UEI.SmartControl( 6760): Registering callback...
I/UEI.SmartControl( 6760): ------ IControl API: 19
I/UEI.SmartControl( 6760): Registering Services Ready callback...
I/UEI.SmartControl( 6760): Notify client services are ready...
I/QRemote ( 7304): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7304): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7304): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7304): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7304): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6760): ------ IControl API: 8
D/QRemote ( 7304): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7304): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7304): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7304): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7304): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7304): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7304): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
I/UEI.SmartControl( 6760): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6760): -----service ready thread exits
V/QRemote ( 7304): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
I/QRemote ( 7304): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7304): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7304): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7304): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7304): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453125434932]
D/QRemote ( 7304): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6721:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/QRemote ( 7304): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
D/QRemote ( 7304): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6721/cgroup.procs: No such file or directory
V/QRemote ( 7304): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7304): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7304): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2686): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3242 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3242 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3242 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3242 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=294411  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=294428  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7304): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
I/wpa_supplicant( 2686): wlan0: Associated with c0:ff:d4:d3:aa:48
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=294515  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=294515  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294516
I/wpa_supplicant( 2686): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2686): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294516
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294516
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294518
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294518
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=294518  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Setting,s.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=294522  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7246): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7246): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7246): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=294523  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=294524  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294524
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294525
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 7246): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7246): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7246): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7246): [AUTORUN] setTetherStatus() : status=false
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
,V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1037): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/CommandListener(  316): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=294573  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=294573  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=294573  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=294580  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=294580  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=294580  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
,D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28620f15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28620f15 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2686): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7158): 
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  316): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
,D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
V/WfdStateTracker( 1934): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/TelephonyNetworkFactory-1( 1845): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
,D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7368): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
,W/dsqn    ( 7368): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
E/DSQN    ( 7368): DSQN ssw
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7304): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7304): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7304): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7304): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7283): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7283): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7246): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7246): MCCMNC not supported: null
D/QRemote ( 7304): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7304): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7304): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7304): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7304): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 13:57:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453125435782], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453125435754]}
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
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1845): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1845):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/dhcpcd  ( 7374): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7374): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7374): version 5.5.6 starting
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
E/dhcpcd  ( 7374): get_duid: m
D/dhcpcd  ( 7374): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7374): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7374): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7374): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7374): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7374): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7374): wlan0: sending REQUEST (xid 0x7cccc1d5), next in 3.21 seconds
I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7158): 
,I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7158): 
,I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7158): 
,I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7158): 
,I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7158): 
,I/jxcore-log( 7158): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7158): 
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7396 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7396): onCreate
W/AppUp4:DB( 7396):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7396):  setFingerPrint start
I/AppUp4:DB( 7396):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/jxcore-log( 7158): Test app app.js loaded
I/jxcore-log( 7158): 
I/AppUp4:DB( 7396):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7396):  SDK version = 21
I/AppUp4:DB( 7396):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7396): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] request level :IDLE....
I/chromium( 7158): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/AppUp4:CustModeStarterReceiver( 7396): onReceive
I/chromium( 7158): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7158): 
D/LgDataFeature( 7396): LgDataFeature() Constructor: none
D/LgDataFeature( 7396): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7396): Context : android.app.ReceiverRestrictedContext@229aa00
D/AppUp4:CustFacade( 7396): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7396): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7396): begin check event
I/AppUp4:CustModeStarterReceiver( 7396): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7396): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7396): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7396): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7396): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6790:com.lge.eula/1000 (adj 15): empty #17
I/chromium( 7158): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6790/cgroup.procs: No such file or directory
D/LGDMClient( 4333): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4333): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3381): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/jxcore-log( 7158): --= Surplus to requirements =--
I/jxcore-log( 7158): 
I/jxcore-log( 7158): ****TEST TOOK:  ms ****
I/jxcore-log( 7158): 
I/jxcore-log( 7158): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7158): 
V/DownloadManager( 3381): DownloadService onCreate
D/LGDMClient( 4333): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4333): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4333): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4333): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3381): in removeSpuriousFiles
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4333): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@3a387f24 on behalf of 3381
D/LGDMClient( 4333): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
D/LGDMClient( 4333): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3381): in trimDatabase
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@3aa34a8d on behalf of 3381
V/DownloadManager( 3381): DownloadService onStartCommand
V/DownloadManager( 3381): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@2e106990 on behalf of 3381
D/eas_req ( 6619): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3381): processing inserted download 1
V/DownloadManager( 3381): processing inserted download 4
V/DownloadManager( 3381): processing inserted download 7
V/DownloadManager( 3381): processing inserted download 8
V/DownloadManager( 3381): processing inserted download 9
V/DownloadManager( 3381): processing inserted download 10
V/DownloadManager( 3381): processing inserted download 16
V/DownloadManager( 3381): processing inserted download 17
V/DownloadManager( 3381): processing inserted download 18
V/DownloadManager( 3381): processing inserted download 21
V/DownloadManager( 3381): processing inserted download 22
V/DownloadManager( 3381): DownloadService onDestroy
I/chromium( 7158): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7158): 
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7431 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 6619): JNI_OnLoad()
I/HubEmail( 6619): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6619): registerNatives()
I/HubEmail( 6619): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6619): registerNativeMethods()
I/HubEmail( 6619): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6619): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3327): networkInfo.isConnected() = false
I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7454 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 7374): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7374): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7374): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7374): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7374): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7374): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7374): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7374): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7374): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524295
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7488 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6742:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6742/cgroup.procs: No such file or directory
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
D/WeatherAncestor( 6927): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:17
D/Weather.Utils( 6927): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6927): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6927): 2 : This is isUpdating : false
D/WeatherAncestor( 6927): connectivity changed - connection : true
D/WeatherService( 6927): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b36d07e
D/ForecastDataCache( 6927): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6927): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6927): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6927): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6927): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:17
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7514 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6005:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6005/cgroup.procs: No such file or directory
,V/FormManager( 7431): There are no updated forms. The schedule will be deleted.
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
V/FormManager( 7431): Alarm would be updated, because LastCheckTime has been updated.
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager( 1037): Killing 6818:com.lge.bnr/1000 (adj 15): empty #17
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/AndroidRuntime( 7531): 
D/AndroidRuntime( 7531): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7531): CheckJNI is OFF
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6818/cgroup.procs: No such file or directory
,D/AndroidRuntime( 7531): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 7158:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1037): WIN DEATH: Window{2ab8fb09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
,D/InputDispatcher( 1037): Window went away: Window{2ab8fb09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{19b6b051 com.example.hello/10319} due to missing metadata
,I/WebViewFactory( 7514): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/art     ( 1037): Explicit concurrent mark sweep GC freed 87938(4MB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 2.998ms total 158.913ms
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{38a58cba u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{3306a3f6 7158:com.test.thalitest/u0a311}, curProc for 7158: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{38a58cba u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{38a58cba u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2025): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2025): [Launcher.java:903:onResume()]onResume
,I/[LGHome]EVENT( 2025): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/[LGHome]Launcher.Model( 2025): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/ActionManagerService( 1898): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2025): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/LibraryLoader( 7514): Loading: webviewchromium
,I/[LGHome]LGActivityUtil( 2025): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2025): [Launcher.java:1056:onResume()]onResume end
I/LibraryLoader( 7514): Time to load native libraries: 11 ms (timestamps 7337-7348)
I/LibraryLoader( 7514): Expected native library version number "",actual native library version number ""
I/[LGHome]EVENT( 2025): [Launcher.java:1114:onPause()]onPause
,V/WebViewChromiumFactoryProvider( 7514): Binding Chromium to main looper Looper (main, tid 1) {23fd2eb}
D/ActionManagerService( 1898): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2025): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000004)
I/LibraryLoader( 7514): Expected native library version number "",actual native library version number ""
I/chromium( 7514): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
V/BoardContentProvider( 3712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2025): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2025): , create_time: 1430558575574
I/GBoardWebViewUtils( 2025): , expire_time: 0
I/GBoardWebViewUtils( 2025): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2025): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2025): , display: false
I/GBoardWebViewUtils( 2025): , animation: false }
I/GBoardWebViewUtils( 2025): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2025): , create_time: 1430558575600
I/GBoardWebViewUtils( 2025): , expire_time: 0
I/GBoardWebViewUtils( 2025): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2025): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2025): , display: false
I/GBoardWebViewUtils( 2025): , animation: false }
I/GBoardWebViewUtils( 2025): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2025): , create_time: 1452774039338
I/GBoardWebViewUtils( 2025): , expire_time: 0
I/GBoardWebViewUtils( 2025): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2025): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2025): , display: false
I/GBoardWebViewUtils( 2025): , animation: false }
,D/WallpaperManager( 2025): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1471): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15cfb02f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
I/BrowserStartupController( 7514): Initializing chromium process, renderers=0
W/art     ( 7514): Attempt to remove local handle scope entry from IRT, ignoring
I/[LGHome]GBoardWebView( 2025): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 4561): Explicit concurrent mark sweep GC freed 16234(920KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 472us total 79.689ms
W/chromium( 7514): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7514): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7514): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{22922650 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1934): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1934): topRunningActivity=ActivityInfo{31c6e049 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
V/AudioPolicyService(  323): registerClient() client 0xb14fdc40, uid 10093
W/AudioManagerAndroid( 7514): Requires BLUETOOTH permission
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1810): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [+] updateMediaPlayerInfo
I/Adreno-EGL( 7514): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7514): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7514): Build Date: 12/12/14 금
I/Adreno-EGL( 7514): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7514): Remote Branch: 
I/Adreno-EGL( 7514): Local Patches: 
I/Adreno-EGL( 7514): Reconstruct Branch: 
D/LIA_Service_RemotePackageHandler( 1987): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3712): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,W/System.err( 4512): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4512): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4512): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4512): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4512): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4512): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4512): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4512): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4512): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4512): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4512): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4512): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/administrator( 1037): Handling package changes for user 0
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7588 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/SplitUIManager( 1862): split_name #11 / not available #0
D/SplitUIService( 1862): removed split : 
,I/[SystemUI]QSlideListController( 1471): onReceive = android.intent.action.PACKAGE_REMOVED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1471): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/SplitUIManager( 1862): split_name #11 / not available #0
I/SplitUIService( 1862): split app #11
I/LockScreenSettings( 7588): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1471): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/KeyguardModel( 1471): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3810): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]Launcher.Model( 2025): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/art     ( 1037): Explicit concurrent mark sweep GC freed 6827(410KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.769ms total 270.984ms
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/ActivityManager( 1037): Killing 6949:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/[LGHome]EVENT( 2025): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2025): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/NSApplication( 7514): Starting up...
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2025): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2025): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2025): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2025): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2025): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/ThermalEngine(  338): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3139): Thermal-Lib-Client: Client request sent
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardModel( 1471): handleShortcutListChanged...
,D/[Concierge]Service( 2589): onStartCommand(). Type : 8
,D/[Concierge]Service( 2589): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{125e7297 u0 com.lge.launcher2/.Launcher t3} time:297705
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6949/cgroup.procs: No such file or directory
D/[Concierge]WidgetView( 2025): change position of spinner
D/[Concierge]Service( 2589): Update widget ID : 11
I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/KeyguardModel( 1471): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
I/[Concierge]WidgetView( 2025): initWebView(). Time : 1453125438674
D/[Concierge]Service( 2589): onStartCommand(). Type : 0
D/KeyguardModel( 1471): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
D/AndroidRuntime( 7531): Shutting down VM
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7614 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6968:com.android.calendar/u0a13 (adj 15): empty #17
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297763235290; DSPS: 9897839; Offset : -4310337106
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/KeyguardModel( 1471): handleShortcutListChanged...
,I/[Concierge]WebView( 2025): Return exist ConciergeWebView. Reuse : 810937906
D/[Concierge]WidgetView( 2025): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2025): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/libprocessgroup( 1037): failed to open /acct/uid_10013/pid_6968/cgroup.procs: No such file or directory
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[LgeWidgetLib]ExtViewHost( 2025): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@22662008
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2025): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2025): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2025): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/ResourcesManager( 7614): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/[Concierge]WidgetView( 2025): Widget kill message received. Destory myself. My : 1453125168516, New one : 1453125438674
D/[Concierge]WidgetView( 2025): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2025): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2025): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2025): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2025): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2025): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2025): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2025): Timeline: Activity_idle id: android.os.BinderProxy@269d136d time:297871
,I/GLSActivity( 2062): [ac] getting account id
,I/GLSUser ( 2062): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/ChimeraCfgMgr( 2348): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2348): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7396): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7396): onReceive
,D/AppUp4:CustFacade( 7396): Context : android.app.ReceiverRestrictedContext@229aa00
D/AppUp4:CustFacade( 7396): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7396): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7396): begin check event
I/AppUp4:CustModeStarterReceiver( 7396): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4333): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4333): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/chromium( 2025): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3381): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2062): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2062): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2062): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2062): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3381): DownloadService onCreate
I/DownloadManager( 3381): in removeSpuriousFiles
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4333): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4333): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4333): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@538028e on behalf of 3381
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3381): in trimDatabase
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/LGDMClient( 4333): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@233a8ebc on behalf of 3381
V/DownloadManager( 3381): DownloadService onStartCommand
V/DownloadManager( 3381): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@bb5b99a on behalf of 3381
V/DownloadManager( 3381): processing inserted download 1
V/DownloadManager( 3381): processing inserted download 4
V/DownloadManager( 3381): processing inserted download 7
W/ContextImpl( 4333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,W/Settings( 6619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3381): processing inserted download 8
E/LGDMClient( 4333): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4333): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4333): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3327): networkInfo.isConnected() = false
W/Settings( 6619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3381): processing inserted download 9
,D/WeatherAncestor( 6927): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:18
I/GBoardtInterface( 2025): onReloaded()
D/Weather.Utils( 6927): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6927): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6927): 2 : This is isUpdating : false
D/WeatherAncestor( 6927): connectivity changed - connection : true
D/WeatherService( 6927): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b36d07e
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 6927): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6927): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6927): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6927): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6927): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:18
V/DownloadManager( 3381): processing inserted download 10
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/GBoardWebViewClient( 2025): onPageFinished url:file:///android_asset/www/main.html
V/DownloadManager( 3381): processing inserted download 16
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/BoardContentProvider( 3712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/DownloadManager( 3381): processing inserted download 17
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3381): processing inserted download 18
V/DownloadManager( 3381): processing inserted download 21
D/ActionManagerService( 1898): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3712): onEvent() : ACTION_BOARD_ENABLED
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
V/DownloadManager( 3381): processing inserted download 22
D/ActionManagerService( 1898): notifyUserLog: 1000001
V/BoardContentProvider( 3712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{1a7fdaa8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3712): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3712): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3712): onSettingEvent() : GBoard On - add scheduler - 0
,D/GBoardUriUtils( 2025): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2025): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
V/DownloadManager( 3381): DownloadService onDestroy
D/GBoardUriUtils( 2025): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2025): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2025): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2025): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/ChimeraCfgMgr( 2348): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/Kids    ( 2348): [AccountUtils] Account not ready
W/Kids    ( 2348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2348): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2348): 	at java.lang.Thread.run(Thread.java:818)
,D/AppUp4:PreloadHelper( 7396): added Exclude : com.test.thalitest
I/GLSUser ( 2062): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2062): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2062): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2062): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7659 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/FileUtils( 2062): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Kids    ( 2348): [AccountUtils] Account not ready
W/Kids    ( 2348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2348): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2348): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2348): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
W/ResourcesManager( 7659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7659): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7659): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 7659): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7659): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{1a7fdaa8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798

```
