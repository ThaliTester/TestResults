#### Test 54970261fc259e9_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257595230644; DSPS: 8581575; Offset : -4304658862
,D/AndroidRuntime( 7028): 
D/AndroidRuntime( 7028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7028): CheckJNI is OFF
D/AndroidRuntime( 7028): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1922): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{3e282a9b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{3e282a9b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7043 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7028): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1833): Display #0 changed.
D/SplitWindowPolicy( 1922): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1922): topRunningActivity=ActivityInfo{1014dd9e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1922): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1922): topRunningActivity=ActivityInfo{3a9cb07f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7043): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7043): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7043): Loading: webviewchromium
I/LibraryLoader( 7043): Time to load native libraries: 3 ms (timestamps 1384-1387)
I/LibraryLoader( 7043): Expected native library version number "",actual native library version number ""
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 27204(1183KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.672ms total 86.911ms
,V/WebViewChromiumFactoryProvider( 7043): Binding Chromium to main looper Looper (main, tid 1) {1ffcd4ce}
I/LibraryLoader( 7043): Expected native library version number "",actual native library version number ""
I/chromium( 7043): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7043): Initializing chromium process, renderers=0
,W/art     ( 7043): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  329): registerClient() client 0xb14fd5c0, uid 10311
,D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bdf3a4d:true
W/chromium( 7043): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7043): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7043): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7043): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7043): Build Date: 12/12/14 금
I/Adreno-EGL( 7043): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7043): Remote Branch: 
I/Adreno-EGL( 7043): Local Patches: 
I/Adreno-EGL( 7043): Reconstruct Branch: 
,W/chromium( 7043): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7043): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7043): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7043): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7043): CordovaWebView is running on device made by: LGE
,W/art     ( 7043): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7043): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7043): Render dirty regions requested: true
I/OpenGLRenderer( 7043): Initialized EGL, version 1.4
D/OpenGLRenderer( 7043): Enabling debug mode 0
,D/Atlas   ( 7043): Validating map...
,D/SplitWindow( 1039): check instance of lgWin Window{2789df5f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1039): Activity pause timeout for ActivityRecord{2f78e38 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7043): LgDataFeature() Constructor: none
D/LgDataFeature( 7043): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1465): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@bea93be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +639ms (total +747ms)
I/Timeline( 7043): Timeline: Activity_idle id: android.os.BinderProxy@7ae0d7e time:271887
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{2f78e38 u0 com.test.thalitest/.MainActivity t4} time:271887
,I/chromium( 7043): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7043): 
,D/JsMessageQueue( 7043): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7043): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434836736
D/JX-Cordova( 7043): jxcore cordova android initializing
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7043): Initializing JXcore engine
W/jxcore-log( 7043): JXcore engine is ready
,W/jxcore-log( 7043): Starting JXcore engine
W/.test.thalitest( 7043): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8877]" dev="sockfs" ino=8877 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7043): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7043): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10443]" dev="sockfs" ino=10443 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7043): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7043): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33379]" dev="sockfs" ino=33379 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7043): Background sticky concurrent mark sweep GC freed 125440(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.791ms total 118.603ms
,W/jxcore-log( 7043): Platform android
W/jxcore-log( 7043): 
W/jxcore-log( 7043): Process ARCH arm
W/jxcore-log( 7043): 
,I/jxcore-log( 7043): JXcore Cordova bridge is ready!
I/jxcore-log( 7043): 
W/jxcore-log( 7043): JXcore engine is started
I/jxcore-log( 7043): Toggling radios to true
I/jxcore-log( 7043): 
D/BluetoothAdapter( 7043): enable(): BT is already enabled..!
D/WifiService( 1039): New client listening to asynchronous messages
D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=7043, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=7043, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=7043, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1039): [274,481,864 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1039): reconnect pid=7043, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7043): Radios toggled
I/jxcore-log( 7043): 
I/wpa_supplicant( 2611): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1039): InitialState.processMessage what=4
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/CommandListener(  325): Clearing all IP addresses on wlan0
V/NativeCrypto( 2052): Read error: ssl=0xaf4d5600: I/O error during system call, Connection timed out
D/DhcpStateMachine( 1039): RunningState{ when=-16ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2052): SSL shutdown failed: ssl=0xaf4d5600: I/O error during system call, Broken pipe
E/WifiStateMachine( 1039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1039):  DisconnectingState CMD_RECONNECT 0 0
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20( 1039): hidePasspointNotification off =false
D/ConnectivityService( 1039): ignoring duplicate network state non-change
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1039): [274,612,403 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
I/wpa_supplicant( 2611): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=274617
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=274618
D/LGWifiP2pService( 1039): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1039): SET ps 1: returned true
V/WfdStateTracker( 1922): handleWifiStateChangedEvent: 0
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524292
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=-9ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-9ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 7134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 7134): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7134): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CommandListener(  325): Clearing all IP addresses on wlan0
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/NetworkManagementService( 1039): Removing idletimer
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/TelephonyNetworkFactory-1( 1833): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1833):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=274687  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=274687  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=274692  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=274694  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7134): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7134): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7134): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7134): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-194ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7170 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6067:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6067/cgroup.procs: No such file or directory
I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7170): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7134): LgDataFeature() Constructor: none
D/LgDataFeature( 7134): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7195 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1039): Killing 6090:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_6090/cgroup.procs: No such file or directory
,W/ResourcesManager( 7195): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7195): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7195): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7195): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7195): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7195): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7195): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7195): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7195): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 7195): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7170): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7170): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7170): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7195): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7195): LgDataFeature() Constructor: none
,D/LgDataFeature( 7195): LgDataFeature() Constructor Done, null
V/SoundPool( 7195): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7195): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7195): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7195): doLoad: loading sample sampleID=1
I/QRemote ( 7195): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7195): Start decode
V/MediaPlayer[Native]( 7195): decode(31, 10857164, 17813)
V/MediaPlayerService(  329): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  329): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  329): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  329): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  329): player type = 3
V/AwesomePlayer(  329): AwesomePlayer create()
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): setAudioSink() 
V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb5474880, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/Utils   (  329): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  329): setDataSource_l dataSource
V/LGParserOSAL(  329): SniffLGParser start
V/LGParserOSAL(  329): MainType:5, SubType=0
V/LGParserOSAL(  329): #### check Mime : application/ogg
V/LGParserOSAL(  329): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  329): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6753): QS Service created
D/QRemote ( 7195): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7195): Create singleton instance
V/LGParserOSAL(  329): supported mime: application/ogg
V/AwesomePlayer(  329): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  329): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  329): mBitrate = -1 bits/sec
V/AwesomePlayer(  329): AudioTrack Setting
V/AwesomePlayer(  329): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  329): setAudioSource() 
V/MediaPlayerService(  329): prepare
V/AwesomePlayer(  329): prepareAsync_l() 
V/MediaPlayerService(  329): wait for prepare
V/AwesomePlayer(  329): onPrepareAsyncEvent() 
V/AwesomePlayer(  329): initAudioDecoder() 
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  329): isAudioPlaybackHookOn() false
V/AwesomePlayer(  329): getUseOffload() = 0 
V/OMXCodec(  329): OMXCodec::Create
V/OMXCodec(  329): findMatchingCodecs()
V/OMXCodec(  329): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  329): matchingCodecs.size()=1
V/OMXCodec(  329): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  329): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  329): LG Codec Adapter start
V/OMXCodec(  329): OMXCodec Createtor
V/OMXCodec(  329): setComponentRole
V/OMXCodec(  329): configureCodec protected=0
V/LGCodecAdapter(  329): called getLGCodecSpecificData
V/LGCodecOSAL(  329): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMSG
V/LGCodecOSAL(  329): Not support LGCodec
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  329): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  329): Could not offload audio decode, try pcm offload
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  329): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  329): init()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  329): allocateBuffers
V/OMXCodec(  329): allocateBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf60 on output port
V/OMXCodec(  329): init() mAsyncCompletion wait!!! 
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  329): init() mAsyncCompletion wait!!! 
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  329): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  329): finishAsyncPrepare_l() 
V/AudioCache(  329): notify(0xb5474880, 5, 0, 0)
V/AudioCache(  329): ignored
V/AudioCache(  329): notify(0xb5474880, 1, 0, 0)
V/AudioCache(  329): prepared
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): start
V/AwesomePlayer(  329): play_l() 
V/AwesomePlayer(  329): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  329): createAudioPlayer_l
V/AwesomePlayer(  329): seekAudioIfNecessary_l() 
V/AwesomePlayer(  329): startAudioPlayer_l() 
D/AudioPlayer(  329): start of Playback, useOffload 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  329): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  329): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796224
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797664
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  329): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb16620b0 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  329): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  329): noti,fy(0xb5474880, 6, 0, 0)
V/AudioCache(  329): ignored
V/MediaPlayerService(  329): wait for playback complete
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab602000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab603000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab604000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab605000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab606000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab607000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab608000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab609000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60a000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60b000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60c000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60d000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60e000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab60f000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab610000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab611000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab612000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab613000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab614000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab615000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab616000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab617000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab618000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab619000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61a000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61b000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61c000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61d000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61e000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab61f000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab620000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab621000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab622000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab623000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab624000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab625000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab626000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab627000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab628000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab629000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62a000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62b000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62c000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62d000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62e000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab62f000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab630000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab631000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab632000, 0xb57db000, 4096)
V/AudioCache(  329): write(0xb57db000, 4096)
V/AudioCache(  329): memcpy(0xab633000, 0xb57db000, 4096)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  329): postAudioEOS() 
V/AudioCache(  329): write(0xb57db000, 280)
V/AudioCache(  329): memcpy(0xab634000, 0xb57db000, 280)
V/AwesomePlayer(  329): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  329): onStreamDone
V/AwesomePlayer(  329): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  329): notify(0xb5474880, 2, 0, 0)
V/AudioCache(  329): playback complete
V/AwesomePlayer(  329): pause_l() 
V/AudioCache(  329): notify(0xb5474880, 7, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  329): Pause Playback at 1068125
V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb5474880, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/AudioPlayer(  329): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb16620b0 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca60 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  329): AudioPlayer releasing audio source
D/AudioPlayer(  329): AudioPlayer done releasing audio source
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): ~AwesomePlayer call
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
,V/SoundPool( 7195): close(31)
V/SoundPool( 7195): pointer = 0x9ffd1000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6753): Service initServices...
D/UEI.SmartControl( 6753): QS start get config
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7195): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3690
I/UEI.SmartControl( 6753): Supports setup maps: true
D/UEI.SmartControl( 6753): QS start statue = true Error code = 0
I/UEI.SmartControl( 6753): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6753): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6753): ### init IR Blaster...
D/serial_port( 6753): Configuring serial port
E/UEI.SmartControl( 6753): UEIBLaster setting for 616
I/UEI.SmartControl( 6753): Setting serial record hearder size = 2
I/UEI.SmartControl( 6753): configuring settings for MAXQ616
I/UEI.SmartControl( 6753): Get version...
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3439d2b0 type 2 when 258762 android} when 258762
D/UEI.SmartControl( 6753): serial port data available: 21
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{3ef08529 type 0 when 1452011396313 android} when 1452011396313
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3bb160ae type 2 when 276055 com.google.android.gms} when 276055
E/WifiStateMachine( 1039):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:210771] from screen [on:0 period:312451505]
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/UEI.SmartControl( 6753): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6753): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6753): QS saving settings...
D/UEI.SmartControl( 6753): IR Blaster version: 25672567
D/UEI.SmartControl( 6753): serial port data available: 4
I/UEI.SmartControl( 6753): Device manager: loading config....
D/UEI.SmartControl( 6753): ----------- loading internal config...
W/ContextImpl( 6753): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6753): Services init done
D/UEI.SmartControl( 6753): QS Service init finished
D/UEI.SmartControl( 6753): QS Service version name: 2.1.91
D/UEI.SmartControl( 6753): QS Service version code: 201091
D/UEI.SmartControl( 6753): Service requested: Control
E/UEI.SmartControl( 6753): Loading SETTINGS...
D/UEI.SmartControl( 6753): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6753): Internal service binding...
I/QRemote ( 7195): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6753): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6753): ------ IControl API: 11
D/UEI.SmartControl( 6753): File observer start...
E/UEI.SmartControl( 6753): IR Port is disabled: false
D/UEI.SmartControl( 6753): Starting file observer...
I/UEI.SmartControl( 6753): Registering callback...
I/UEI.SmartControl( 6753): ------ IControl API: 19
I/UEI.SmartControl( 6753): Registering Services Ready callback...
I/UEI.SmartControl( 6753): Notify client services are ready...
I/UEI.SmartControl( 6753): Notify AllClients services are ready: 0
I/QRemote ( 7195): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/QRemote ( 7195): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6753): -----service ready thread exits
D/QRemote ( 7195): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7195): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7195): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7195): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6753): ------ IControl API: 8
D/QRemote ( 7195): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7195): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7195): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7195): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7195): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7195): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7195): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7195): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452011397672]
D/QRemote ( 7195): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1039): Killing 6484:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 7195): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_6484/cgroup.procs: No such file or directory
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/wpa_supplicant( 2611): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=276744  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=276756  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2611): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=276843  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=276844  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=276845
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=276845
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=276846
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=276846
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=276846
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7134): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=276847  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2611): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2611): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=276850  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 7134): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7134): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7134): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 7134): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=276863  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=276863  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=276864
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=276864
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1039): Got NetworkAgent Messenger
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1039): NetworkAgent connected
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/CommandListener(  325): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 2
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=276914  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=276914  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=276915  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1039): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=276918  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=276918  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=276918  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c9a9e40 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c9a9e40 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
D/CommandListener(  325): Setting iface cfg
D/CommandListener(  325): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1039): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2611): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 101
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1922): handleWifiStateChangedEvent: 1
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  325): netlink response contains error (File exists)
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1039): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1833): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1833):   my score=50, my f,ilter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/dsqn    ( 7267): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7267): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type(),
E/DSQN    ( 7267): DSQN ssw
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7195): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7195): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7195): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7170): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7170): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7134): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/WiFiOffLoadBroadcast( 7134): MCCMNC not supported: null
W/dhcpcd  ( 7271): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7271): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
D/QRemote ( 7195): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7195): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7195): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/dhcpcd  ( 7271): version 5.5.6 starting
E/dhcpcd  ( 7271): get_duid: m
D/dhcpcd  ( 7271): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7271): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/LGDataListener(  325): argv[0]=dsqncommand
D/LGDataListener(  325): argv[1]=wlan0
D/LGDataListener(  325): argv[2]=1
D/LGDataListener(  325): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
,D/dhcpcd  ( 7271): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7271): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7271): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7271): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7271): wlan0: sending REQUEST (xid 0xdf6fe1b), next in 3.55 seconds
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 16:29:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452011398716], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452011398694]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
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
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1833): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1833):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277600208282; DSPS: 9237099; Offset : -4304685820
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
D/Tethering( 1039): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5401): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5401): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7301 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7301): onCreate
,W/AppUp4:DB( 7301):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7301):  setFingerPrint start
I/AppUp4:DB( 7301):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7301):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7301):  SDK version = 21
I/AppUp4:DB( 7301):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7301): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7301): onReceive
D/LgDataFeature( 7301): LgDataFeature() Constructor: none
D/LgDataFeature( 7301): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@10ef4afc
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7301): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7301): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7301): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7301): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 6599:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6599/cgroup.procs: No such file or directory
,D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3322): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3322): DownloadService onCreate
I/DownloadManager( 3322): in removeSpuriousFiles
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7329 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     (  361): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 21.459ms
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 17.592ms
,V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@2c8f3219 on behalf of 3322
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 27.123ms
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3322): in trimDatabase
,V/DownloadManager( 3322): DownloadService onStartCommand
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@741ef8c on behalf of 3322
V/DownloadManager( 3322): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@57d6d5 on behalf of 3322
V/DownloadManager( 3322): processing inserted download 1
V/DownloadManager( 3322): processing inserted download 4
W/ResourcesManager( 7329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/DownloadManager( 3322): processing inserted download 7
W/ResourcesManager( 7329): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/DownloadManager( 3322): processing inserted download 8
W/ResourcesManager( 7329): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7329): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3322): processing inserted download 9
V/DownloadManager( 3322): processing inserted download 10
V/DownloadManager( 3322): processing inserted download 16
V/DownloadManager( 3322): processing inserted download 17
V/DownloadManager( 3322): processing inserted download 18
V/DownloadManager( 3322): processing inserted download 21
,V/DownloadManager( 3322): DownloadService onDestroy
I/LGEmail ( 7329): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7329): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7329): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7329): LgDataFeature() Constructor: none
D/LgDataFeature( 7329): LgDataFeature() Constructor Done, null
,D/eas_req ( 7329): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7357 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7329): JNI_OnLoad()
I/HubEmail( 7329): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7329): registerNatives()
I/HubEmail( 7329): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7329): registerNativeMethods()
I/HubEmail( 7329): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7329): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1039): Killing 6627:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1039):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7271): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1039): identical MTU - not setting
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524295
I/dhcpcd  ( 7271): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7271): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7271): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7271): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7271): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7271): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7271): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7271): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_6627/cgroup.procs: No such file or directory
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3263): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3263): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3263): networkInfo.isConnected() = false
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7396 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1f20d6be type 2 when 278919 com.google.android.gms} when 278919
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1039): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7425 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6656:com.google.android.apps.docs/u0a61 (adj 15): empty #17
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6656/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7446 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6705:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_6705/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Killing 6782:com.lge.eula/1000 (adj 15): empty #17
,I/art     ( 7446): Almond Protected OAT
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6782/cgroup.procs: No such file or directory
,D/WeatherApplication( 7446): removeAccount
D/WeatherApplication( 7446): Account.length = 0
E/WeatherApplication( 7446): OPERATOR:OPEN
D/WeatherAncestor( 7446): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:0
,D/Weather.Utils( 7446): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7446): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7446): 2 : This is isUpdating : false
D/WeatherAncestor( 7446): connectivity changed - connection : true
D/WeatherService( 7446): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7446): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7446): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7446): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7446): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7446): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:1
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7464 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6732:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_6732/cgroup.procs: No such file or directory
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7464): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7464): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7464): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7464): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,I/WebViewFactory( 7464): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7464): Loading: webviewchromium
,I/LibraryLoader( 7464): Time to load native libraries: 8 ms (timestamps 134-142)
I/LibraryLoader( 7464): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7464): Binding Chromium to main looper Looper (main, tid 1) {1507bed7}
,I/LibraryLoader( 7464): Expected native library version number "",actual native library version number ""
I/chromium( 7464): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5401): type=WIFI subType= reason=null isConnected=true
I/BrowserStartupController( 7464): Initializing chromium process, renderers=0
W/art     ( 7464): Attempt to remove local handle scope entry from IRT, ignoring
,D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/chromium( 7464): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7464): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7464): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  329): registerClient() client 0xb14fd860, uid 10093
W/AudioManagerAndroid( 7464): Requires BLUETOOTH permission
I/Adreno-EGL( 7464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7464): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7464): Build Date: 12/12/14 금
I/Adreno-EGL( 7464): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7464): Remote Branch: 
I/Adreno-EGL( 7464): Local Patches: 
I/Adreno-EGL( 7464): Reconstruct Branch: 
,I/NSApplication( 7464): Starting up...
,I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7519 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6809:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6809/cgroup.procs: No such file or directory
,W/ResourcesManager( 7519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2312): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/ChimeraCfgMgr( 2312): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7301): onReceive
,D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@10ef4afc
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3322): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3322): DownloadService onCreate
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3322): in removeSpuriousFiles
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2312): [AccountUtils] Account not ready
W/Kids    ( 2312): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2312): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2312): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
I/GLSActivity( 2052): [ac] getting account id
I/art     ( 1039): Explicit concurrent mark sweep GC freed 83254(3MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.494ms total 125.270ms
,V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@2be955db on behalf of 3322
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
V/DownloadManager( 3322): DownloadService onStartCommand
V/DownloadManager( 3322): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3322): in trimDatabase
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@39f9afb6 on behalf of 3322
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@1f9d74b7 on behalf of 3322
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/DownloadManager( 3322): processing inserted download 1
V/DownloadManager( 3322): processing inserted download 4
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2052): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3322): processing inserted download 7
V/DownloadManager( 3322): processing inserted download 8
V/DownloadManager( 3322): processing inserted download 9
V/DownloadManager( 3322): processing inserted download 10
I/LgeMiscReceiver( 3263): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3263): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3263): networkInfo.isConnected() = false
V/DownloadManager( 3322): processing inserted download 16
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3322): processing inserted download 17
V/DownloadManager( 3322): processing inserted download 18
V/DownloadManager( 3322): processing inserted download 21
D/WeatherAncestor( 7446): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:2
V/DownloadManager( 3322): DownloadService onDestroy
,D/Weather.Utils( 7446): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7446): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7446): 2 : This is isUpdating : false
D/WeatherAncestor( 7446): connectivity changed - connection : true
D/WeatherService( 7446): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@24956fda
D/ForecastDataCache( 7446): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7446): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7446): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7446): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7446): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:2
D/ChimeraCfgMgr( 2312): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7301): onReceive
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@10ef4afc
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3322): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
V/DownloadManager( 3322): DownloadService onCreate
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4298): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  325): res_queryN name = mtalk.google.com succeed
D/LGDMClient( 4298): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DownloadManager( 3322): in removeSpuriousFiles
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4298): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@20691142 on behalf of 3322
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3322): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3322): in trimDatabase
V/DownloadManager( 3322): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3322): DownloadService onStartCommand
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@319de90 on behalf of 3322
V/DownloadManager( 3322): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3322): created cursor android.database.sqlite.SQLiteCursor@2733d389 on behalf of 3322
V/DownloadManager( 3322): processing inserted download 1
V/DownloadManager( 3322): processing inserted download 4
V/DownloadManager( 3322): processing inserted download 7
V/DownloadManager( 3322): processing inserted download 8
,V/DownloadManager( 3322): processing inserted download 9
V/DownloadManager( 3322): processing inserted download 10
V/DownloadManager( 3322): processing inserted download 16
V/DownloadManager( 3322): processing inserted download 17
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3322): processing inserted download 18
V/DownloadManager( 3322): processing inserted download 21,
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3322): DownloadService onDestroy
,I/LgeMiscReceiver( 3263): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3263): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3263): networkInfo.isConnected() = true
D/PhoneState( 3263): setPdpRejectCasuse : false
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4298): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4298): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4298): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/Kids    ( 2312): [AccountUtils] Account not ready
W/Kids    ( 2312): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2312): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2312): 	at java.lang.Thread.run(Thread.java:818)
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/WeatherAncestor( 7446): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:2
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
,D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/Weather.Utils( 7446): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7446): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7446): 2 : This is isUpdating : false
D/WeatherAncestor( 7446): connectivity changed - connection : true
D/WeatherService( 7446): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@24956fda
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/ForecastDataCache( 7446): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7446): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7446): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7446): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7446): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:30:2
,D/UEI.SmartControl( 6753): Internal timer expired: 3
D/UEI.SmartControl( 6753): unbind internal service
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2312): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7577 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/serial_port( 6753): close(fd = 24)
,I/UEI.SmartControl( 6753): Serial port is closed.
I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.google.com, class = 1, type = 1
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2312): [AccountUtils] Account not ready
W/Kids    ( 2312): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2312): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2312): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2312): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2312): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2312): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
I/DigitalAppWidgetProvider( 7577): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 7577): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3f6eb5c9
,D/libc-netbsd(  325): res_queryN name = www.google.com succeed
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3690
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/GCM     ( 2052): Connected
D/GCM     ( 2052): Message class com.google.f.a.a.p
V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7043): Test app app.js loaded
I/jxcore-log( 7043): 
,I/chromium( 7043): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7043): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7043): 
,I/chromium( 7043): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager( 1039): Killing 6833:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_6833/cgroup.procs: No such file or directory
,I/GAV4    ( 7464): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1039): Killing 6907:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_6907/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 297602258744; DSPS: 9892526; Offset : -4304680399
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{28797148 type 2 when 305990 android} when 305990
,I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7621 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7621): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7621): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7621): Created application version: 3.2.35 (30235)
,I/BooksSync( 7621): Starting books sync
,D/BooksSync( 7621): started syncMyEbooks
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/HttpHelper( 7621): null auth token
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4000760838013755194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
W/ApiaryClient( 7621): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4000760838013755194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 20095(925KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 3.033ms total 183.305ms
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
W/ApiaryClient( 7621): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4000760838013755194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
,E/BooksSync( 7621): Soft error: 
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4000760838013755194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
,E/BooksSync( 7621): Sync error
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4000760838013755194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
I/BooksSync( 7621): Finished books sync
I/ActivityManager( 1039): Killing 6186:com.android.vending/u0a44 (adj 15): empty #17
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305990, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_6186/cgroup.procs: No such file or directory
I/GAV2    ( 7621): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 317604185507; DSPS: 10547949; Offset : -4304676480
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{32e57ca2 type 2 when 336090 android} when 336090
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 337606455811; DSPS: 11203383; Offset : -4304664475
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 357608445491; DSPS: 11858808; Offset : -4304658334
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 377611266213; DSPS: 12514261; Offset : -4304676007
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 397613339017; DSPS: 13169689; Offset : -4304678398
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 417614950312; DSPS: 13825101; Offset : -4304654018
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 437616969835; DSPS: 14480528; Offset : -4304679042
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 457619117953; DSPS: 15135958; Offset : -4304667154
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 477621905342; DSPS: 15791409; Offset : -4304656943
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 497623999761; DSPS: 16446838; Offset : -4304668186
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 517628288399; DSPS: 17102339; Offset : -4304682499
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 537630891517; DSPS: 17757784; Offset : -4304673402
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 557632754842; DSPS: 18413205; Offset : -4304671624
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1efb9d33 type 2 when 571537 android} when 571537
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/ChimeraCfgMgr( 2312): Loading module com.google.android.gms.games from APK com.google.android.gms
I/BooksSync( 7621): Starting books sync
,D/BooksSync( 7621): started syncMyEbooks
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5732323051744116612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5732323051744116612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
W/ApiaryClient( 7621): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5732323051744116612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
,E/BooksSync( 7621): Soft error: 
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5732323051744116612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
,E/BooksSync( 7621): Sync error
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5732323051744116612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
I/BooksSync( 7621): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 571537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 577634937595; DSPS: 19068636; Offset : -4304655489
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 597636798472; DSPS: 19724057; Offset : -4304656209
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{6fb97bd type 2 when 601756 android} when 601756
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 617638629662; DSPS: 20379477; Offset : -4304656074
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 637641108614; DSPS: 21034919; Offset : -4304679642
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 657643307929; DSPS: 21690351; Offset : -4304677462
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/LEDHandler( 1922): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1922): Battery Level Remaining: 100%
,D/LEDHandler( 1922): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3756): Disconnected process message: 10, size: 0
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 677645205265; DSPS: 22345773; Offset : -4304672320
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 697647228174; DSPS: 23001199; Offset : -4304663650
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 717649909884; DSPS: 23656647; Offset : -4304667278
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 737652141024; DSPS: 24312080; Offset : -4304664129
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 757654041901; DSPS: 24967502; Offset : -4304655187
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 777656847570; DSPS: 25622954; Offset : -4304657056
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 797658729386; DSPS: 26278376; Offset : -4304667512
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3a8961b2 type 2 when 817590 android} when 817590
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 817661734482; DSPS: 26933834; Offset : -4304652384
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/LEDHandler( 1922): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1922): Battery Level Remaining: 100%
D/LEDHandler( 1922): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3756): Disconnected process message: 10, size: 0
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 837663963746; DSPS: 27589268; Offset : -4304682124
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 857665976082; DSPS: 28244693; Offset : -4304653352
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 877668079876; DSPS: 28900122; Offset : -4304655271
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 897669956795; DSPS: 29555544; Offset : -4304670493
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 917672167309; DSPS: 30210976; Offset : -4304657167
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 937674359801; DSPS: 30866408; Offset : -4304661941
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,W/bt-smp  ( 3756): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3756): Plain text(LSB ~ MSB) = e2 eb 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3756): Encrypted text(LSB ~ MSB) = dd 32 83 e9 83 0a 24 0a 46 c0 fc bb 1b 81 97 1b 
,W/bt-btm  ( 3756): Stopping oneshot timer
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{9ef0503 type 2 when 943131 com.android.bluetooth} when 943131
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 957676632710; DSPS: 31521843; Offset : -4304677850
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 977678524629; DSPS: 32177265; Offset : -4304678151
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 997680597277; DSPS: 32832693; Offset : -4304680724
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1017682813885; DSPS: 33488125; Offset : -4304661279
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1037684111065; DSPS: 34143528; Offset : -4304676250
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1057686173037; DSPS: 34798955; Offset : -4304659137
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1077688294747; DSPS: 35454385; Offset : -4304673476
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{319e3c80 type 2 when 1096877 android} when 1096877
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,I/BooksSync( 7621): Starting books sync
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1097689795000; DSPS: 36109794; Offset : -4304668402
D/BooksSync( 7621): started syncMyEbooks
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  325): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782072474584815111&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782072474584815111&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2052): Explicit concurrent mark sweep GC freed 37817(2MB) AllocSpace objects, 24(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.234ms total 66.023ms
,I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2052): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2052): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2052): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2052): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2052): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7621): Authentication error
E/BooksAccountManager( 7621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7621): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7621): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{2c24a424 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7621): Error response from books API: {
W/ApiaryClient( 7621):  "error": {
W/ApiaryClient( 7621):   "errors": [
W/ApiaryClient( 7621):    {
W/ApiaryClient( 7621):     "domain": "global",
W/ApiaryClient( 7621):     "reason": "required",
W/ApiaryClient( 7621):     "message": "Login Required",
W/ApiaryClient( 7621):     "locationType": "header",
W/ApiaryClient( 7621):     "location": "Authorization"
W/ApiaryClient( 7621):    }
W/ApiaryClient( 7621):   ],
W/ApiaryClient( 7621):   "code": 401,
W/ApiaryClient( 7621):   "message": "Login Required"
W/ApiaryClient( 7621):  }
W/ApiaryClient( 7621): }
,W/ApiaryClient( 7621): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782072474584815111&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7621): Headers:
W/ApiaryClient( 7621): accept-encoding: [gzip]
W/ApiaryClient( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7621): gdata-version: 2
E/BooksSync( 7621): Soft error: 
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782072474584815111&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
,E/BooksSync( 7621): Sync error
E/BooksSync( 7621): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7621): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782072474584815111&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7621): Headers:
E/BooksSync( 7621): accept-encoding: [gzip]
E/BooksSync( 7621): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7621): gdata-version: 2
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7621): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7621): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7621): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7621): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7621): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7621): {
E/BooksSync( 7621):  "error": {
E/BooksSync( 7621):   "errors": [
E/BooksSync( 7621):    {
E/BooksSync( 7621):     "domain": "global",
E/BooksSync( 7621):     "reason": "required",
E/BooksSync( 7621):     "message": "Login Required",
E/BooksSync( 7621):     "locationType": "header",
E/BooksSync( 7621):     "location": "Authorization"
E/BooksSync( 7621):    }
E/BooksSync( 7621):   ],
E/BooksSync( 7621):   "code": 401,
E/BooksSync( 7621):   "message": "Login Required"
E/BooksSync( 7621):  }
E/BooksSync( 7621): }
E/BooksSync( 7621): 
E/BooksSync( 7621): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7621): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7621): 	... 8 more
I/BooksSync( 7621): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1096877, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1117692580879; DSPS: 36765245; Offset : -4304659779
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{46e406a type 2 when 1127667 android} when 1127667
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1137696498266; DSPS: 37420734; Offset : -4304679315
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1157698586175; DSPS: 38076162; Offset : -4304666628
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1177700789658; DSPS: 38731594; Offset : -4304660410
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/DigitalAppWidgetProvider( 7577): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7577): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3f6eb5c9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1197702848712; DSPS: 39387022; Offset : -4304676526
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1217704982715; DSPS: 40042452; Offset : -4304678831
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1237706891718; DSPS: 40697874; Offset : -4304661788
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1257709057856; DSPS: 41353305; Offset : -4304662450
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1277711088162; DSPS: 42008732; Offset : -4304676874
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1297713211383; DSPS: 42664161; Offset : -4304659236
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1317715342572; DSPS: 43319591; Offset : -4304664381
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1337717586471; DSPS: 43975025; Offset : -4304678862
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1357719410422; DSPS: 44630444; Offset : -4304655291
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1377721687707; DSPS: 45285879; Offset : -4304666824
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1397723809574; DSPS: 45941309; Offset : -4304681319
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1417725961180; DSPS: 46596739; Offset : -4304665917
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1437728126433; DSPS: 47252170; Offset : -4304667229
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1457730792051; DSPS: 47907617; Offset : -4304656771
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1477732518397; DSPS: 48563034; Offset : -4304669875
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1497734702504; DSPS: 49218465; Offset : -4304652595
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1517736569736; DSPS: 49873887; Offset : -4304677347
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1537738735717; DSPS: 50529318; Offset : -4304678219
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1557741458471; DSPS: 51184767; Offset : -4304671503
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1577743703724; DSPS: 51840201; Offset : -4304684395
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1597745557050; DSPS: 52495621; Offset : -4304662306
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1617747743135; DSPS: 53151053; Offset : -4304673487
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1637749831565; DSPS: 53806481; Offset : -4304660121
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1657752501714; DSPS: 54461929; Offset : -4304675572
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1677754650092; DSPS: 55117359; Offset : -4304663476
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1697756490292; DSPS: 55772779; Offset : -4304654408
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1717758342628; DSPS: 56428200; Offset : -4304663646
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1737760904131; DSPS: 57083644; Offset : -4304665566
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1757762643135; DSPS: 57739061; Offset : -4304665960
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1777764785783; DSPS: 58394491; Offset : -4304659543
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1797767021712; DSPS: 59049925; Offset : -4304682097
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/HeadsetStateMachine( 3756): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1922): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1922): Battery Level Remaining: 100%
D/LEDHandler( 1922): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4298): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1817768889882; DSPS: 59705346; Offset : -4304675369
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1837770501021; DSPS: 60360759; Offset : -4304681869
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,W/bt-smp  ( 3756): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3756): Plain text(LSB ~ MSB) = e3 51 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3756): Encrypted text(LSB ~ MSB) = f6 7a d0 bb d7 ee b7 be a9 c0 5f c8 a6 81 49 68 
,W/bt-btm  ( 3756): Stopping oneshot timer
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{ee845f8 type 2 when 1843159 com.android.bluetooth} when 1843159
I/ProcessStatsService( 1039): Prepared write state in 21ms
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/ProcessStatsService( 1039): Prepared write state in 16ms
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=482265989 [*alarm*], flags=0x0
,I/ProcessStatsService( 1039): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-36-26.bin
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{34078ad1 type 0 when 1452012300924 com.google.android.gms} when 1452012300924
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2227f936 type 2 when 1181361 com.google.android.gms} when 1181361
,D/GCM     ( 2052): Message class com.google.f.a.a.i
,D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
I/GLSUser ( 2052): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2052): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2052): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2052): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2312): Aggregate from 1452010500850 (log), 1452010500850 (data)
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 46760(2MB) AllocSpace objects, 18(1293KB) LOS objects, 33% free, 44MB/66MB, paused 1.827ms total 115.635ms
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1857772149710; DSPS: 61016173; Offset : -4304680896
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1877775025588; DSPS: 61671627; Offset : -4304673801
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1897777197924; DSPS: 62327058; Offset : -4304668160
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1917779114270; DSPS: 62982481; Offset : -4304674447
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1937781365722; DSPS: 63637915; Offset : -4304681140
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1957791421652; DSPS: 64293604; Offset : -4304665676
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1977793263936; DSPS: 64949025; Offset : -4304684782
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1997795078668; DSPS: 65604444; Offset : -4304670640
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 2017797215118; DSPS: 66259874; Offset : -4304670550
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 2037799074798; DSPS: 66915295; Offset : -4304672285
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 2057801374114; DSPS: 67570730; Offset : -4304661762
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 2077803048064; DSPS: 68226145; Offset : -4304666384
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=482265989, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Killing 7134:com.android.settings/1000 (adj 15): empty for 1803s
I/ActivityManager( 1039): Killing 7170:com.lge.sync/1000 (adj 15): empty for 1803s
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7134/cgroup.procs: No such file or directory
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7170/cgroup.procs: No such file or directory
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7577): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 7577): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3f6eb5c9
,TIME-OUT KILL (timeout was 1800000ms)
```
