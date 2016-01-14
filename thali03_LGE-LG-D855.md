#### Test 55613145c131883_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/AndroidRuntime( 7292): 
D/AndroidRuntime( 7292): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7292): CheckJNI is OFF
D/AndroidRuntime( 7292): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1066): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1958): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1066): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1066): setTaskToReturnTo : TaskRecord{16fa4493 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1066): setTaskToReturnTo : TaskRecord{16fa4493 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1066): AppWindowTokenEx init.. 
E/GBMv2   (  333): DFP En is all cleared set to be enabled
I/ActivityManager( 1066): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7312 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7292): Shutting down VM
V/ActivityManager( 1066): Display changed displayId=0
D/DSDPConnection( 1852): Display #0 changed.
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{25f51448 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{d37c2e1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7312): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7312): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7312): Loading: webviewchromium
I/LibraryLoader( 7312): Time to load native libraries: 4 ms (timestamps 3119-3123)
I/LibraryLoader( 7312): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7312): Binding Chromium to main looper Looper (main, tid 1) {923795b}
,I/LibraryLoader( 7312): Expected native library version number "",actual native library version number ""
I/chromium( 7312): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7312): Initializing chromium process, renderers=0
W/art     ( 7312): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  313): registerClient() client 0xb54f5f20, uid 10311
,W/chromium( 7312): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7312): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7312): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1066): Message: 20
D/BluetoothManagerService( 1066): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dc485:true
I/Adreno-EGL( 7312): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7312): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7312): Build Date: 12/12/14 금
I/Adreno-EGL( 7312): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7312): Remote Branch: 
I/Adreno-EGL( 7312): Local Patches: 
I/Adreno-EGL( 7312): Reconstruct Branch: 
,W/chromium( 7312): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7312): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7312): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7312): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7312): CordovaWebView is running on device made by: LGE
,W/art     ( 7312): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7312): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7312): Render dirty regions requested: true
I/OpenGLRenderer( 7312): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7312): Enabling debug mode 0
D/Atlas   ( 7312): Validating map...
,D/SplitWindow( 1066): check instance of lgWin Window{2df265d7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7312): LgDataFeature() Constructor: none
D/LgDataFeature( 7312): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1066): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1066): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1066): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1066): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a60d646,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1066): Displayed com.test.thalitest/.MainActivity: +605ms (total +708ms)
,I/Timeline( 7312): Timeline: Activity_idle id: android.os.BinderProxy@3cf16f4b time:293551
I/Timeline( 1066): Timeline: Activity_windows_visible id: ActivityRecord{26262cd0 u0 com.test.thalitest/.MainActivity t4} time:293551
D/JsMessageQueue( 7312): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7312): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434849024
,D/JX-Cordova( 7312): jxcore cordova android initializing
E/GBMv2   (  333): DFP En is all cleared set to be enabled
E/GBMv2   (  333): Set value is all cleared set the max
I/GBMv2   (  333): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7312): Initializing JXcore engine
W/jxcore-log( 7312): JXcore engine is ready
,W/jxcore-log( 7312): Starting JXcore engine
W/.test.thalitest( 7312): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10313]" dev="sockfs" ino=10313 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7312): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7312): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9846]" dev="sockfs" ino=9846 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7312): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7312): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[35999]" dev="sockfs" ino=35999 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7312): Background sticky concurrent mark sweep GC freed 124849(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.630ms total 138.875ms
,W/jxcore-log( 7312): Platform android
W/jxcore-log( 7312): 
W/jxcore-log( 7312): Process ARCH arm
W/jxcore-log( 7312): 
I/jxcore-log( 7312): JXcore Cordova bridge is ready!
I/jxcore-log( 7312): 
W/jxcore-log( 7312): JXcore engine is started
I/jxcore-log( 7312): Toggling radios to true
I/jxcore-log( 7312): 
D/BluetoothAdapter( 7312): enable(): BT is already enabled..!
D/WifiService( 1066): New client listening to asynchronous messages
D/WifiServiceImplEx( 1066): setWifiEnabled: true pid=7312, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1066): setWifiEnabled: true pid=7312, uid=10311
E/WifiService( 1066): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1066): disconnect pid=7312, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1066):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1066):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1066): [295,710,993 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1066): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1066): reconnect pid=7312, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7312): Radios toggled
I/jxcore-log( 7312): 
I/jxcore-log( 7312): My device name is: LGE-LG-D855
I/jxcore-log( 7312): 
I/wpa_supplicant( 2660): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1066): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1066): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiNative-wlan0( 1066): DISCONNECT: returned true
E/WifiStateMachine( 1066): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1066): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1066): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1066): InitialState.processMessage what=4
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1066): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1066): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1066): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1066): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1066): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1066): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1066): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1066): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1066): doBoolean: SET ps 1
D/WifiNative-wlan0( 1066): SET ps 1: returned true
D/CommandListener(  307): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1066): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1066): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7383 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2169): Read error: ssl=0xaa70aa00: I/O error during system call, Connection timed out
D/ConnectivityService( 1066): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1066): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1066): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1066):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1066):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1066): [295,820,579 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1066): doBoolean: RECONNECT
I/wpa_supplicant( 2660): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1066): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1066): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1066): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 0
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1066): hidePasspointNotification off =false
D/WifiNative-wlan0( 1066): RECONNECT: returned true
E/WifiStateMachine( 1066):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=295859
E/WifiStateMachine( 1066):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=295859
D/LGWifiP2pService( 1066): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1066): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1066): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1066): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1066): doBoolean: SET ps 1
D/WifiNative-wlan0( 1066): SET ps 1: returned true
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  307): Clearing all IP addresses on wlan0
D/ConnectivityService( 1066): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1066): disableDataServiceNotify
D/DSQN    ( 1066): stop dsqn bin
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=295885  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=295885  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1066): hidePasspointNotification off =false
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1066):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1066):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1066): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1066): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1066): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1066):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1066): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1066):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1066): Removing idletimer
E/WifiStateMachine( 1066):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1066): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService( 1066): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1066):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): Disconnected - quitting
V/NetworkPolicy( 1066): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1852): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiNetworkAgent( 1066): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=295894  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/NetworkPolicy( 1066): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1066): Sending msg: 4 arg1:0 arg2:1
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=295898  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1066): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1066):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7383): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7383): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7383): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7383): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7383): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 1066): Explicit concurrent mark sweep GC freed 37603(1767KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.710ms total 141.019ms
D/LocSvc_java( 1066): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1066): hidePasspointNotification off =false
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateSCANNING
D/LocSvc_java( 1066): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1066): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1066): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1066): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1066): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1066): ignore wifi update if we are not in OPENING or CLOSING
V/NativeCrypto( 2169): SSL shutdown failed: ssl=0xaa70aa00: I/O error during system call, Broken pipe
D/DhcpStateMachine( 1066): StoppedState
D/DhcpStateMachine( 1066): StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7383): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7383): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7383): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7383): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7383): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7383): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1066): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7418 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1066): Killing 6209:com.android.contacts/u0a19 (adj 15): empty #17
I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 22.181ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.007ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 20.696ms
W/libprocessgroup( 1066): failed to open /acct/uid_10019/pid_6209/cgroup.procs: No such file or directory
I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7418): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7383): LgDataFeature() Constructor: none
D/LgDataFeature( 7383): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
I/ActivityManager( 1066): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7439 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1066): Killing 6823:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1066): failed to open /acct/uid_10023/pid_6823/cgroup.procs: No such file or directory
W/ResourcesManager( 7439): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7439): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7439): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7439): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7439): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7439): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7439): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7439): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7439): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7439): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7439): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7418): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7418): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7418): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
,D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7439): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7439): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7439): LgDataFeature() Constructor: none
D/LgDataFeature( 7439): LgDataFeature() Constructor Done, null
,V/SoundPool( 7439): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7439): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7439): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7439): doLoad: loading sample sampleID=1
,I/QRemote ( 7439): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7439): Start decode
V/MediaPlayer[Native]( 7439): decode(31, 10857164, 17813)
,D/UEI.SmartControl( 6891): QS Service created
V/MediaPlayerService(  313): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  313): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  313): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  313): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  313): player type = 3
V/AwesomePlayer(  313): AwesomePlayer create()
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): setAudioSink() 
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1432c40, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  313): Use LGExtractor :application/ogg 
D/QRemote ( 7439): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7439): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 6891): Service initServices...
D/UEI.SmartControl( 6891): QS start get config
V/LGMDMManager( 7439): Create singleton instance
V/LGParserOSAL(  313): supported mime: application/ogg
V/AwesomePlayer(  313): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  313): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  313): mBitrate = -1 bits/sec
V/AwesomePlayer(  313): AudioTrack Setting
V/AwesomePlayer(  313): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  313): setAudioSource() 
V/MediaPlayerService(  313): prepare
V/AwesomePlayer(  313): prepareAsync_l() 
V/MediaPlayerService(  313): wait for prepare
V/AwesomePlayer(  313): onPrepareAsyncEvent() 
V/AwesomePlayer(  313): initAudioDecoder() 
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  313): isAudioPlaybackHookOn() false
V/AwesomePlayer(  313): getUseOffload() = 0 
V/OMXCodec(  313): OMXCodec::Create
V/OMXCodec(  313): findMatchingCodecs()
V/OMXCodec(  313): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  313): matchingCodecs.size()=1
V/OMXCodec(  313): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  313): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  313): LG Codec Adapter start
V/OMXCodec(  313): OMXCodec Createtor
V/OMXCodec(  313): setComponentRole
V/OMXCodec(  313): configureCodec protected=0
V/LGCodecAdapter(  313): called getLGCodecSpecificData
V/LGCodecOSAL(  313): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMSG
V/LGCodecOSAL(  313): Not support LGCodec
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  313): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  313): Could not offload audio decode, try pcm offload
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  313): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  313): init()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  313): allocateBuffers
V/OMXCodec(  313): allocateBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  313): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  313): finishAsyncPrepare_l() 
V/AudioCache(  313): notify(0xb1432c40, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb1432c40, 1, 0, 0)
V/AudioCache(  313): prepared
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): start
V/AwesomePlayer(  313): play_l() 
V/AwesomePlayer(  313): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  313): createAudioPlayer_l
V/AwesomePlayer(  313): seekAudioIfNecessary_l() 
V/AwesomePlayer(  313): startAudioPlayer_l() 
D/AudioPlayer(  313): start of Playback, useOffload 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  313): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  313): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb1432c40, 6, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab700000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab701000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab702000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab703000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab704000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab705000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab706000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab707000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab708000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab709000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70a000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70b000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70c000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70d000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70e000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab70f000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab710000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab711000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab712000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab713000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab714000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab715000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab716000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab717000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab718000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab719000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71a000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71b000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71c000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71d000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71e000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab71f000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab720000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab721000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab722000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab723000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab724000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab725000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab726000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab727000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab728000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab729000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72a000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72b000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72c000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72d000, 0xb17c8000, 4096)
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72e000, 0xb17c8000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab72f000, 0xb17c8000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab730000, 0xb17c8000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  313): write(0xb17c8000, 4096)
V/AudioCache(  313): memcpy(0xab731000, 0xb17c8000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb17c8000, 280)
V/AudioCache(  313): memcpy(0xab732000, 0xb17c8000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb1432c40, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): notify(0xb1432c40, 7, 0, 0)
V/AudioCache(  313): wait - success
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  313): Pause Playback at 1068125
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1432c40, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/AudioPlayer(  313): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  313): AudioPlayer releasing audio source
D/AudioPlayer(  313): AudioPlayer done releasing audio source
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): ~AwesomePlayer call
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/SoundPool( 7439): close(31)
V/SoundPool( 7439): pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7439): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3174,
I/UEI.SmartControl( 6891): Supports setup maps: true
D/UEI.SmartControl( 6891): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6891): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6891): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6891): ### init IR Blaster...
,D/serial_port( 6891): Configuring serial port
E/UEI.SmartControl( 6891): UEIBLaster setting for 616
I/UEI.SmartControl( 6891): Setting serial record hearder size = 2
I/UEI.SmartControl( 6891): configuring settings for MAXQ616
I/UEI.SmartControl( 6891): Get version...
D/UEI.SmartControl( 6891): serial port data available: 21
,D/UEI.SmartControl( 6891): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6891): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6891): QS saving settings...
D/UEI.SmartControl( 6891): IR Blaster version: 25672567
,D/UEI.SmartControl( 6891): serial port data available: 4
,W/ContextImpl( 6891): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6891): Services init done
D/UEI.SmartControl( 6891): QS Service init finished
I/UEI.SmartControl( 6891): Device manager: loading config....
D/UEI.SmartControl( 6891): ----------- loading internal config...
D/UEI.SmartControl( 6891): QS Service version name: 2.1.91
D/UEI.SmartControl( 6891): QS Service version code: 201091
D/UEI.SmartControl( 6891): Service requested: Control
,D/UEI.SmartControl( 6891): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6891): Loading SETTINGS...
D/UEI.SmartControl( 6891): Internal service binding...
,I/QRemote ( 7439): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6891): ------ IControl API: 11
D/UEI.SmartControl( 6891): File observer start...
E/UEI.SmartControl( 6891): IR Port is disabled: false
,D/UEI.SmartControl( 6891): Starting file observer...
I/UEI.SmartControl( 6891): Registering callback...
I/UEI.SmartControl( 6891): ------ IControl API: 19
I/UEI.SmartControl( 6891): Registering Services Ready callback...
D/UEI.SmartControl( 6891): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6891): Notify AllClients services are ready: 0
,I/QRemote ( 7439): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6891): -----service ready thread exits
D/QRemote ( 7439): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7439): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7439): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7439): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6891): ------ IControl API: 8
D/QRemote ( 7439): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7439): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7439): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7439): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 7439): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7439): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7439): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7439): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7439): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7439): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7439): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452774072570]
D/QRemote ( 7439): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1066): Killing 6237:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/QRemote ( 7439): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1066): failed to open /acct/uid_10027/pid_6237/cgroup.procs: No such file or directory
,V/QRemote ( 7439): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7439): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7439): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/sensors_hal_Time( 1066): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1066): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1066): tsOffsetIs: Apps: 297921010307; DSPS: 9903018; Offset : -4309297107
,E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 2660): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1066): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1066): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1066): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1066):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1066):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1066):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1066):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1066): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=297972  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=297987  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2660): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1066): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298072  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298072  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1066):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298073
E/WifiStateMachine( 1066):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298073
D/Tethering( 1066): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1066):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298074
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298074
E/WifiStateMachine( 1066):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298075
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298075  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298077  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2660): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2660): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7383): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7383): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7383): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1066): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1066): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1066): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/St,atusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateASSOCIATED
,E/WifiStateMachine( 1066):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1066):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1066):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateFOUR_WAY_HANDSHAKE
D/UsbSettingsControl( 7383): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7383): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7383): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7383): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1066):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298086  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298088  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1066):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298088
E/WifiStateMachine( 1066):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298089
D/WifiNative-wlan0( 1066): doString: [STATUS]
D/WifiMonitor( 1066): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1066): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1066):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1066): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
I/WifiServerServiceExt( 1066): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1066): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1066): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1066): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1066): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1066): Got NetworkAgent Messenger
D/ConnectivityService( 1066): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1066): NetworkAgent connected
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1066): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1066): doBoolean: SAVE_CONFIG
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1066): SAVE_CONFIG: returned true
E/WifiConfigStore( 1066): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1066): doBoolean: SET_NETWORK 0 bssid any
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1066): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1066): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1066): SAVE_CONFIG: returned true
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  307): Setting iface cfg
E/WifiStateMachine( 1066): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1066): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1066):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298124  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1066): WaitBeforeStartState
E/WifiStateMachine( 1066):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298125  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298125  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1066): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1066):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298126  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1066):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298127  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1066):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298127  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1066):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1066):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1066):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1066): doBoolean: DRIVER SETSUSPENDMODE 0
,V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1066): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1066): doBoolean: SET ps 0
D/WifiNative-wlan0( 1066): SET ps 0: returned true
D/WifiNative-wlan0( 1066): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1066): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1066): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1066): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1066): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1066): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@174c3e1f target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1066): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@174c3e1f target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1066): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1066): DHCP Start wake lock is acquired.
D/CommandListener(  307): Setting iface cfg
D/CommandListener(  307): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1066): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1066): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1066): setSupplicantStateCOMPLETED
,E/WifiStateMachine( 1066):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1066):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1066): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1066):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1066):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,D/LGWifiP2pService( 1066): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1066): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1066): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1066): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1066): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2660): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1066): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1066): doBoolean: SET ps 1
D/WifiNative-wlan0( 1066): SET ps 1: returned true
D/ConnectivityService( 1066): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1066):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1066):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1066): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1066): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1066): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine( 1066): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1066): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1066): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 1
D/WifiHS20( 1066): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1066): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1066): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1066): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1066): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1066): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1066): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  307): netlink response contains error (File exists)
D/ConnectivityService( 1066): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1066): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1066): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1066): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1066): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1066): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1066):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1066):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1066): currentScore = 0, newScore = 20
D/ConnectivityService( 1066):    accepting network in place of null
D/ConnectivityService( 1066): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1066): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1066):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1066): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1066): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1066): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1066): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1066): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1066): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1066): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1066): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1066): ignore wifi update if we are not in OPENING or CLOSING
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
D/ConnectivityService( 1066): validation of new default Network = false
D/ConnectivityService( 1066): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1066): enableDataServiceNotify 
D/DSQN    ( 1066): start dsqn bin
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1066): [LG_RESTRICTED] checkMobilePolicy_type()
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/ConnectivityService( 1066): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
W/dsqn    ( 7496): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7496): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7496): DSQN ssw
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7439): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  307): argv[0]=dsqncommand
D/LGDataListener(  307): argv[1]=wlan0
D/LGDataListener(  307): argv[2]=1
D/LGDataListener(  307): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1066): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1066): start to monitor internet connection
D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7439): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7439): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7439): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7418): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7418): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:21:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452774073569], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452774073550]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1066): Validated
D/ConnectivityService( 1066): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/WiFiOffLoadBroadcast( 7383): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1066):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1066): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1066): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
D/WIFI    ( 1066): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1066):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/WiFiOffLoadBroadcast( 7383): MCCMNC not supported: null
D/QRemote ( 7439): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7439): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7439): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7439): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7439): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1066): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1066): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1066): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7502): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7502): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7502): version 5.5.6 starting
E/dhcpcd  ( 7502): get_duid: m
D/dhcpcd  ( 7502): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7502): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7502): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7502): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7502): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7502): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7502): wlan0: sending REQUEST (xid 0x5ded75f5), next in 3.96 seconds
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1066): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1066): MasterInitialState.processMessage what=3
,D/Tethering( 1066): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5962): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1066): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1066): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1066): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5962): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1066): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7529 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7529): onCreate
,W/AppUp4:DB( 7529):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7529):  setFingerPrint start
I/AppUp4:DB( 7529):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7529):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7529):  SDK version = 21
I/AppUp4:DB( 7529):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7529): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7529): onReceive
D/LgDataFeature( 7529): LgDataFeature() Constructor: none
D/LgDataFeature( 7529): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7529): Context : android.app.ReceiverRestrictedContext@2bff9ad1
D/AppUp4:CustFacade( 7529): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7529): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7529): begin check event
I/AppUp4:CustModeStarterReceiver( 7529): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7529): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7529): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7529): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7529): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1066): Killing 6720:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1066): failed to open /acct/uid_10004/pid_6720/cgroup.procs: No such file or directory
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4332): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3368): DownloadService onCreate
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3368): in removeSpuriousFiles
,V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4332): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3e67dba5 on behalf of 3368
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@2f006f2b on behalf of 3368
,I/ActivityManager( 1066): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7556 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3368): DownloadService onStartCommand
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@d1f8d21 on behalf of 3368
,V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
V/DownloadManager( 3368): processing inserted download 7
E/LGDMClient( 4332): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4332): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4332): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
,V/DownloadManager( 3368): processing inserted download 21
V/DownloadManager( 3368): DownloadService onDestroy
W/ResourcesManager( 7556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7556): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7556): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7556): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7556): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7556): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7556): LgDataFeature() Constructor: none
,D/LgDataFeature( 7556): LgDataFeature() Constructor Done, null
,D/PowerManagerServiceEx( 1066): acquireWakeLockInternal: lock=1063077094, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1066
V/AlarmManager( 1066): ELAPSED_WAKEUP set : Alarm{36189566 type 2 when 299596 com.google.android.gms} when 299596
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/eas_req ( 7556): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3315): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3315): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3315): networkInfo.isConnected() = false
,I/HubEmail( 7556): JNI_OnLoad()
I/HubEmail( 7556): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7556): registerNatives()
I/HubEmail( 7556): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7556): registerNativeMethods()
I/HubEmail( 7556): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7556): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1066): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7583 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com, class = 1, type = 1
W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/dhcpcd  ( 7502): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7502): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7502): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7502): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7502): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7502): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7502): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7502): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7502): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1066): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7614 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1066): Killing 6860:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,E/WifiStateMachine( 1066):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1066):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1066):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1066):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1066):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1066): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1066): identical MTU - not setting
D/Nat464Xlat( 1066): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1066): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1066):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1066): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524295
,W/libprocessgroup( 1066): failed to open /acct/uid_10061/pid_6860/cgroup.procs: No such file or directory
D/DhcpStateMachine( 1066): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1066): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1066): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1066): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1066): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1066): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1066): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1066): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1066): RunningState
I/ActivityManager( 1066): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7641 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1066): Killing 6268:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1066): failed to open /acct/uid_10080/pid_6268/cgroup.procs: No such file or directory
,I/art     ( 7641): Almond Protected OAT
,D/WeatherApplication( 7641): removeAccount
D/WeatherApplication( 7641): Account.length = 0
,E/WeatherApplication( 7641): OPERATOR:OPEN
D/WeatherAncestor( 7641): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:15
D/Weather.Utils( 7641): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7641): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7641): 2 : This is isUpdating : false
D/WeatherAncestor( 7641): connectivity changed - connection : true
D/WeatherService( 7641): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7641): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7641): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7641): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7641): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7641): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:15
,I/ActivityManager( 1066): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7659 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1066): Killing 6289:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,V/FormManager( 7148): There are no updated forms. The schedule will be deleted.
V/FormManager( 7148): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1066): failed to open /acct/uid_10097/pid_6289/cgroup.procs: No such file or directory
,I/ActivityManager( 1066): Killing 6935:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1066): failed to open /acct/uid_1000/pid_6935/cgroup.procs: No such file or directory
,V/AlarmManager( 1066): ELAPSED_WAKEUP set : Alarm{29672416 type 2 when 300640 android} when 300640
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7659): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7659): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine( 1066):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1066):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1066):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1066):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1066):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1066):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7659): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7659): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7659): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7659): Loading: webviewchromium
I/LibraryLoader( 7659): Time to load native libraries: 4 ms (timestamps 1040-1044)
,I/LibraryLoader( 7659): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7659): Binding Chromium to main looper Looper (main, tid 1) {160b940}
I/LibraryLoader( 7659): Expected native library version number "",actual native library version number ""
I/chromium( 7659): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7659): Initializing chromium process, renderers=0
W/art     ( 7659): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7659): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7659): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7659): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb558a920, uid 10093
,W/AudioManagerAndroid( 7659): Requires BLUETOOTH permission
I/Adreno-EGL( 7659): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7659): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7659): Build Date: 12/12/14 금
I/Adreno-EGL( 7659): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7659): Remote Branch: 
I/Adreno-EGL( 7659): Local Patches: 
I/Adreno-EGL( 7659): Reconstruct Branch: 
,I/NSApplication( 7659): Starting up...
,I/ActivityManager( 1066): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7718 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1066): Killing 6956:com.lge.bnr/1000 (adj 15): empty #17
,V/WifiInternetCheck( 1066): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1066): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1066): failed to open /acct/uid_1000/pid_6956/cgroup.procs: No such file or directory
,D/Tethering( 1066): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5962): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 7718): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/GpsLocationProvider( 1066): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1066): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/BooksSync( 7048): Starting books sync
D/BooksSync( 7048): started syncMyEbooks
,V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
,D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
W/GLSActivity( 2169): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2169): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2169): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2169): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 7048): Authentication error
E/BooksAccountManager( 7048): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7048): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7048): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7048): null auth token
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  307): res_queryN name = www.googleapis.com succeed
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7529): onReceive
I/GLSActivity( 2169): [ac] getting account id
D/AppUp4:CustFacade( 7529): Context : android.app.ReceiverRestrictedContext@2bff9ad1
D/AppUp4:CustFacade( 7529): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7529): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7529): begin check event
I/AppUp4:CustModeStarterReceiver( 7529): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/ApiaryClient( 7048): Error response from books API: {
W/ApiaryClient( 7048):  "error": {
W/ApiaryClient( 7048):   "errors": [
W/ApiaryClient( 7048):    {
W/ApiaryClient( 7048):     "domain": "global",
W/ApiaryClient( 7048):     "reason": "required",
W/ApiaryClient( 7048):     "message": "Login Required",
W/ApiaryClient( 7048):     "locationType": "header",
W/ApiaryClient( 7048):     "location": "Authorization"
W/ApiaryClient( 7048):    }
W/ApiaryClient( 7048):   ],
W/ApiaryClient( 7048):   "code": 401,
W/ApiaryClient( 7048):   "message": "Login Required"
W/ApiaryClient( 7048):  }
W/ApiaryClient( 7048): }
W/ApiaryClient( 7048): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7048): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=777697771688124777&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7048): Headers:
W/ApiaryClient( 7048): accept-encoding: [gzip]
W/ApiaryClient( 7048): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7048): gdata-version: 2
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2169): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1066): Explicit concurrent mark sweep GC freed 65864(3MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 2.410ms total 135.304ms
,V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3368): DownloadService onCreate
D/LGDMClient( 4332): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3368): in removeSpuriousFiles
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4332): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@194d307 on behalf of 3368
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4332): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4332): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4332): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3368): DownloadService onStartCommand
,V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@1aa17fd2 on behalf of 3368
V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
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
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3a2198a3 on behalf of 3368
V/DownloadManager( 3368): processing inserted download 4
,I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/LgeMiscReceiver( 3315): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3315): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3315): networkInfo.isConnected() = false
V/DownloadManager( 3368): processing inserted download 7
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
D/LgeQuickCoverNLService( 1396): onNotificationPosted
V/DownloadManager( 3368): processing inserted download 21
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/WeatherAncestor( 7641): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:17
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
D/Weather.Utils( 7641): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7641): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7641): 2 : This is isUpdating : false
D/WeatherAncestor( 7641): connectivity changed - connection : true
D/WeatherService( 7641): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d165037
W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ForecastDataCache( 7641): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7641): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7641): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7641): 2 : isUpdateNeedForAlarm : no city return false
V/DownloadManager( 3368): DownloadService onDestroy
D/WeatherAncestor( 7641): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:17
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7148): There are no updated forms. The schedule will be deleted.
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7148): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PowerManagerServiceEx( 1066): releaseWakeLockInternal: lock=1063077094 [*alarm*], flags=0x0
,D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7529): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7529): onReceive
I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/AppUp4:CustFacade( 7529): Context : android.app.ReceiverRestrictedContext@2bff9ad1
D/AppUp4:CustFacade( 7529): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7529): isPhone : true
V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustModeStarterReceiver( 7529): begin check event
I/AppUp4:CustModeStarterReceiver( 7529): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/libc-netbsd(  307): res_queryN name = mtalk.google.com succeed
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNLService( 1396): onNotificationPosted
V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LGDMClient( 4332): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4332): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3368): DownloadService onCreate
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
I/DownloadManager( 3368): in removeSpuriousFiles
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3e9bbf59 on behalf of 3368
,I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3473c71e on behalf of 3368
I/LGDMClient( 4332): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/LgeMiscReceiver( 3315): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3315): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3315): networkInfo.isConnected() = true
D/PhoneState( 3315): setPdpRejectCasuse : false
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4332): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4332): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4332): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7641): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:17
,D/Weather.Utils( 7641): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7641): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7641): 2 : This is isUpdating : false
D/WeatherAncestor( 7641): connectivity changed - connection : true
D/WeatherService( 7641): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3d165037
V/DownloadManager( 3368): DownloadService onStartCommand
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3cbff815 on behalf of 3368
D/ForecastDataCache( 7641): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7641): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7641): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7641): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7641): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:21:17
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
V/DownloadManager( 3368): processing inserted download 7
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
V/DownloadManager( 3368): processing inserted download 21
,W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3368): DownloadService onDestroy
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7148): There are no updated forms. The schedule will be deleted.
V/FormManager( 7148): Alarm would be updated, because LastCheckTime has been updated.
,I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleURLConnFactory( 2169): Using platform SSLCertificateSocketFactory
,V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
W/Uploader( 2169): No account for auth token provided
I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = play.googleapis.com, class = 1, type = 1
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
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  307): res_queryN name = play.googleapis.com succeed
,D/UEI.SmartControl( 6891): Internal timer expired: 2
D/UEI.SmartControl( 6891): unbind internal service
D/GCM     ( 2169): Connected
,D/GCM     ( 2169): Message class com.google.f.a.a.p
D/serial_port( 6891): close(fd = 24)
,I/UEI.SmartControl( 6891): Serial port is closed.
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.google.com, class = 1, type = 1
,W/Uploader( 2169): No account for auth token provided
D/libc-netbsd(  307): res_queryN name = www.google.com succeed
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1066): isHttpConnectionAvailable - We got a valid response : 204
,W/Uploader( 2169):  no longer exists, so no auth token.
,W/Uploader( 2169): No account for auth token provided
,W/Uploader( 2169): No account for auth token provided
V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7312): Test app app.js loaded
I/jxcore-log( 7312): 
,W/Uploader( 2169): No account for auth token provided
,I/chromium( 7312): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7312): 
I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 7312): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
W/GLSActivity( 2169): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2169): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2169): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2169): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7048): Authentication error
E/BooksAccountManager( 7048): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7048): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7048): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7048): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/chromium( 7312): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ApiaryClient( 7048): Error response from books API: {
W/ApiaryClient( 7048):  "error": {
W/ApiaryClient( 7048):   "errors": [
W/ApiaryClient( 7048):    {
W/ApiaryClient( 7048):     "domain": "global",
W/ApiaryClient( 7048):     "reason": "required",
W/ApiaryClient( 7048):     "message": "Login Required",
W/ApiaryClient( 7048):     "locationType": "header",
W/ApiaryClient( 7048):     "location": "Authorization"
W/ApiaryClient( 7048):    }
W/ApiaryClient( 7048):   ],
W/ApiaryClient( 7048):   "code": 401,
W/ApiaryClient( 7048):   "message": "Login Required"
W/ApiaryClient( 7048):  }
W/ApiaryClient( 7048): }
,W/ApiaryClient( 7048): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7048): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=777697771688124777&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7048): Headers:
W/ApiaryClient( 7048): accept-encoding: [gzip]
W/ApiaryClient( 7048): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7048): gdata-version: 2
,I/jxcore-log( 7312): --= Surplus to requirements =--
I/jxcore-log( 7312): 
,I/jxcore-log( 7312): ****TEST TOOK:  ms ****
I/jxcore-log( 7312): 
I/jxcore-log( 7312): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7312): 
I/chromium( 7312): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7312): 
,D/AndroidRuntime( 7806): 
D/AndroidRuntime( 7806): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7806): CheckJNI is OFF
D/AndroidRuntime( 7806): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1066): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1066): Killing 7312:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1066): WIN DEATH: Window{2df265d7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1066): Client connection lost with reason: 4
,D/InputDispatcher( 1066): Window went away: Window{2df265d7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1066): Skipping PackageSetting{1479fe9 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1066):   Force finishing activity ActivityRecord{26262cd0 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  333): DFP En is all cleared set to be enabled
,W/ActivityManager( 1066): Spurious death for ProcessRecord{53fbb79 7312:com.test.thalitest/u0a311}, curProc for 7312: null
I/ActivityManager( 1066): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1066):   Force finishing activity ActivityRecord{26262cd0 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1066): Duplicate finish request for ActivityRecord{26262cd0 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2075): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2075): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{3924b806 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{1f585ec7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2075): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_MrGDBLogger_PackageInfoDetector( 3681): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,D/PostponalbeReceiver( 6767): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/InputReader( 1066): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
W/System.err( 4565): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
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
,I/art     ( 4630): Explicit concurrent mark sweep GC freed 22822(1297KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 43.331ms total 118.152ms
I/ActivityManager( 1066): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7836 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1909): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3681): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2075): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
V/SIM_STK ( 1066): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2075): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2075): [Launcher.java:1114:onPause()]onPause
,D/administrator( 1066): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1444): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1909): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3681): handleMessage: what(1000) actionID(0x1000004)
V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BoardContentProvider( 3681): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1444): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2075): , create_time: 1430558575574
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2075): , create_time: 1430558575600
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
,I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2075): , create_time: 1452774039338
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
D/SplitUIManager( 1869): split_name #11 / not available #0
D/WallpaperManager( 2075): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
V/SIM_STK ( 1066): Menu title from STK is T-Mobile
V/SIM_STK ( 1066): Menu title from STK is T-Mobile
D/SplitUIService( 1869): removed split : 
D/AppUp4:PreloadHelper( 7529): added Exclude : com.test.thalitest
I/SystemUI[Framework]( 1066): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1066): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1066): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1066): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a60d646,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1066): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
,I/ActivityManager( 1066): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7858 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/LockScreenSettings( 7836): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/ActivityManager( 1066): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 2075): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1066): Menu title from STK is T-Mobile
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
,D/KeyguardModel( 1444): handleShortcutListChanged...
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/NotificationService( 1066): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1066): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/JobSchedulerService( 1066): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1066): removeObsoleteFile: deleting file=4_task.xml
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/ThermalEngine(  322): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3137): Thermal-Lib-Client: Client request sent
D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
,W/ResourcesManager( 7858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1444): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/GLSUser ( 2169): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2169): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2169): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2169): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2169): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Timeline( 1066): Timeline: Activity_windows_visible id: ActivityRecord{32a662e u0 com.lge.launcher2/.Launcher t3} time:304380
,V/NotificationService( 1066): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
V/NotificationService( 1066): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1066): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1066): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1066): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2169): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2169): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2169): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2169): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2169): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7048): Authentication error
E/BooksAccountManager( 7048): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7048): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7048): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7048): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7048): null auth token
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll4
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
I/art     ( 1066): Explicit concurrent mark sweep GC freed 25256(1593KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/67MB, paused 3.408ms total 393.508ms
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=4
I/[Concierge]WidgetView( 2075): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2611): onStartCommand(). Type : 8
D/[Concierge]Service( 2611): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2611): Update widget ID : 11
D/[Concierge]WidgetView( 2075): change position of spinner
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3e9bbf59 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[Concierge]WidgetView( 2075): initWebView(). Time : 1452774079570
D/[Concierge]Service( 2611): onStartCommand(). Type : 0
I/SystemConfig( 7858): BUILD Country: EU
I/SystemConfig( 7858): BUILD Operator: OPEN
I/[Concierge]WebView( 2075): Return exist ConciergeWebView. Reuse : 240920383
D/[Concierge]WidgetView( 2075): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2075): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@225a123d
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2075): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2075): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ApiaryClient( 7048): Error response from books API: {
W/ApiaryClient( 7048):  "error": {
W/ApiaryClient( 7048):   "errors": [
W/ApiaryClient( 7048):    {
W/ApiaryClient( 7048):     "domain": "global",
W/ApiaryClient( 7048):     "reason": "required",
W/ApiaryClient( 7048):     "message": "Login Required",
W/ApiaryClient( 7048):     "locationType": "header",
W/ApiaryClient( 7048):     "location": "Authorization"
W/ApiaryClient( 7048):    }
W/ApiaryClient( 7048):   ],
W/ApiaryClient( 7048):   "code": 401,
W/ApiaryClient( 7048):   "message": "Login Required"
W/ApiaryClient( 7048):  }
W/ApiaryClient( 7048): }
W/ApiaryClient( 7048): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7048): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=777697771688124777&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7048): Headers:
W/ApiaryClient( 7048): accept-encoding: [gzip]
W/ApiaryClient( 7048): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7048): gdata-version: 2
,W/[Concierge]WidgetView( 2075): Widget kill message received. Destory myself. My : 1452773802524, New one : 1452774079570
D/[Concierge]WidgetView( 2075): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2075): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1066): Killing 6978:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/AndroidRuntime( 7806): Shutting down VM
,W/ResourcesManager( 1066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1066): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1066): failed to open /acct/uid_10005/pid_6978/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7858): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7858): existFile = false
I/SystemConfig( 7858): canReadFile = false
I/SystemConfig( 7858): systemFeature RCS result false
D/SystemConfig( 7858): refreshRcsSupport() :false
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/VoicemailCleanupService( 2124): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 7556): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1066): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7882 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/art     (  337): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 203us total 18.326ms
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     (  337): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 11.867ms
I/Timeline( 2075): Timeline: Activity_idle id: android.os.BinderProxy@2cfdbeda time:304592
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 9.566ms
W/ResourcesManager( 7882): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7882): Total System Memory = 2995761152
D/SystemHelper( 7882): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1066): Killing 6311:com.android.vending/u0a44 (adj 15): empty #17
I/chromium( 2075): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/LIA_Service_NativeEventReceiver( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2030): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1066): failed to open /acct/uid_10044/pid_6311/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2030): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6767): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardtInterface( 2075): onReloaded()
I/GBoardWebViewClient( 2075): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1066): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7903 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BoardContentProvider( 3681): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3681): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1909): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3681): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3681): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1909): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3681): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3681): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3681): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3681): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3681): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/ActivityThread( 7903): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7903): No ProfileInfo entries
I/LG Account v2.2( 7903): isEnabled: false
I/Feature ( 7903): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7903): [Lifetracker]Country: EU
I/Feature ( 7903): [Lifetracker]Operator: OPEN
I/Feature ( 7903): [Lifetracker]Ranking support: false
I/Feature ( 7903): [Lifetracker]Comfort support: false
I/Feature ( 7903): [Lifetracker]Accessory: true
I/Feature ( 7903): [Lifetracker]Health device: true
I/Feature ( 7903): [Lifetracker]Extra Pedometer: false
I/Feature ( 7903): [Lifetracker]Blood glucose device: false
I/Feature ( 7903): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 7903): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7383): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7383): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7383): replacing : false

```
