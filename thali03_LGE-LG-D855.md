#### Test 549702618c0ebdb_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 257952630840; DSPS: 8593299; Offset : -4307181336
,D/AndroidRuntime( 7043): 
D/AndroidRuntime( 7043): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7043): CheckJNI is OFF
D/AndroidRuntime( 7043): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1034): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 2004): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1034): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{2f08ed62 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{2f08ed62 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1034): AppWindowTokenEx init.. 
E/GBMv2   (  346): DFP En is all cleared set to be enabled
I/ActivityManager( 1034): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7063 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7043): Shutting down VM
V/ActivityManager( 1034): Display changed displayId=0
D/DSDPConnection( 1889): Display #0 changed.
D/SplitWindowPolicy( 2004): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 2004): topRunningActivity=ActivityInfo{31073a03 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 2004): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 2004): topRunningActivity=ActivityInfo{3512cd80 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7063): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7063): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7063): Loading: webviewchromium
I/LibraryLoader( 7063): Time to load native libraries: 3 ms (timestamps 4853-4856)
I/LibraryLoader( 7063): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7063): Binding Chromium to main looper Looper (main, tid 1) {1edf3a73}
I/LibraryLoader( 7063): Expected native library version number "",actual native library version number ""
I/chromium( 7063): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7063): Initializing chromium process, renderers=0
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb14fd6a0, uid 10311
,D/BluetoothManagerService( 1034): Message: 20
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10b24edc:true
W/chromium( 7063): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7063): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7063): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7063): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7063): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7063): Build Date: 12/12/14 금
I/Adreno-EGL( 7063): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7063): Remote Branch: 
I/Adreno-EGL( 7063): Local Patches: 
I/Adreno-EGL( 7063): Reconstruct Branch: 
,W/chromium( 7063): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7063): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7063): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7063): CordovaWebView is running on device made by: LGE
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1034): Activity pause timeout for ActivityRecord{3aed1ef3 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7063): LgDataFeature() Constructor: none
D/LgDataFeature( 7063): LgDataFeature() Constructor Done, null
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 26759(1192KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.974ms total 144.302ms
,D/OpenGLRenderer( 7063): Render dirty regions requested: true
I/OpenGLRenderer( 7063): Initialized EGL, version 1.4
D/OpenGLRenderer( 7063): Enabling debug mode 0
,D/Atlas   ( 7063): Validating map...
D/SplitWindow( 1034): check instance of lgWin Window{17472b36 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ffbc3fb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1034): Displayed com.test.thalitest/.MainActivity: +731ms (total +818ms)
I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{3aed1ef3 u0 com.test.thalitest/.MainActivity t4} time:265418
I/Timeline( 7063): Timeline: Activity_idle id: android.os.BinderProxy@8ba663 time:265421
I/chromium( 7063): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7063): 
D/JsMessageQueue( 7063): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7063): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435088128
D/JX-Cordova( 7063): jxcore cordova android initializing
E/GBMv2   (  346): DFP En is all cleared set to be enabled
,E/GBMv2   (  346): Set value is all cleared set the max
I/GBMv2   (  346): DFP Enabled. Ignore VFP set
W/jxcore-log( 7063): Initializing JXcore engine
W/jxcore-log( 7063): JXcore engine is ready
,W/jxcore-log( 7063): Starting JXcore engine
,W/.test.thalitest( 7063): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6121]" dev="sockfs" ino=6121 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7063): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7063): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7652]" dev="sockfs" ino=7652 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7063): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7063): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33428]" dev="sockfs" ino=33428 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7063): Platform android
W/jxcore-log( 7063): 
W/jxcore-log( 7063): Process ARCH arm
W/jxcore-log( 7063): 
,I/jxcore-log( 7063): JXcore Cordova bridge is ready!
I/jxcore-log( 7063): 
W/jxcore-log( 7063): JXcore engine is started
,I/jxcore-log( 7063): Toggling radios to true
I/jxcore-log( 7063): 
,D/BluetoothAdapter( 7063): enable(): BT is already enabled..!
D/WifiService( 1034): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1034): setWifiEnabled: true pid=7063, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1034): setWifiEnabled: true pid=7063, uid=10311
E/WifiService( 1034): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1034): disconnect pid=7063, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1034):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1034): [268,000,967 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1034): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1034): reconnect pid=7063, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7063): Radios toggled
I/jxcore-log( 7063): 
I/wpa_supplicant( 2645): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1034): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1034): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1034): InitialState.processMessage what=4
D/WifiNative-wlan0( 1034): DISCONNECT: returned true
E/WifiStateMachine( 1034): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
D/DhcpStateMachine( 1034): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Clearing all IP addresses on wlan0
V/NativeCrypto( 2146): Read error: ssl=0xaa76a000: I/O error during system call, Connection timed out
V/NativeCrypto( 2146): SSL shutdown failed: ssl=0xaa76a000: I/O error during system call, Broken pipe
D/Tethering( 1034): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService( 1034): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on "NG700"
I/ActivityManager( 1034): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7135 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1034): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1034):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1034): [268,129,886 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1034): doBoolean: RECONNECT
I/wpa_supplicant( 2645): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1034): RECONNECT: returned true
E/WifiStateMachine( 1034):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268134
D/WifiHS20( 1034): hidePasspointNotification off =false
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268135
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1034): SET ps 1: returned true
V/WfdStateTracker( 2004): handleWifiStateChangedEvent: 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1034): hidePasspointNotification off =false
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1034): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1034): disableDataServiceNotify
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1034): stop dsqn bin
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268182  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268183  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1034):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1034): hidePasspointNotification off =false
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1034): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Disconnected - quitting
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CSLegacyTypeTracker( 1034): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048,576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1034): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1034): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268195  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1034): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1889): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1889):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1034): Removing idletimer
W/Settings( 1034): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1034): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1034): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268205  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1034): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateSCANNING
,W/ResourcesManager( 7135): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7135): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7135): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7135): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7135): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7135): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7135): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7135): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7135): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/DhcpStateMachine( 1034): StoppedState
D/DhcpStateMachine( 1034): StoppedState{ when=-200ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsControl( 7135): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7135): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7135): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1034): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7172 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6104:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10011/pid_6104/cgroup.procs: No such file or directory
,I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7172): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7135): LgDataFeature() Constructor: none
,D/LgDataFeature( 7135): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
I/ActivityManager( 1034): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7196 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1034): Killing 6126:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10019/pid_6126/cgroup.procs: No such file or directory
,W/ResourcesManager( 7196): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7196): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7196): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7196): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7196): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7196): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7196): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7196): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7196): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7172): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/QRemote ( 7196): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7172): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7172): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7196): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7196): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7196): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7196): LgDataFeature() Constructor: none
D/LgDataFeature( 7196): LgDataFeature() Constructor Done, null
,V/SoundPool( 7196): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7196): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7196): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7196): doLoad: loading sample sampleID=1
I/QRemote ( 7196): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7196): Start decode
V/MediaPlayer[Native]( 7196): decode(31, 10857164, 17813)
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
,V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1432c40, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6801): QS Service created
D/QRemote ( 7196): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7196): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7196): Create singleton instance
V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
I/UEI.SmartControl( 6801): Service initServices...
D/UEI.SmartControl( 6801): QS start get config
,V/AwesomePlayer(  316): onPrepareAsyncEvent() 
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
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
V/AudioCache(  316): notify(0xb1432c40, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1432c40, 1, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1432c40, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab700000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab701000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/A,udioCache(  316): memcpy(0xab702000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab703000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab704000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab705000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab706000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab707000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab708000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab709000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70a000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70b000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70c000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70d000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70e000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab70f000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab710000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab711000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab712000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab713000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab714000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab715000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab716000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab717000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab718000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab719000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71a000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71b000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71c000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71d000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71e000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab71f000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab720000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab721000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab722000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab723000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab724000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab725000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab726000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab727000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab728000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab729000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72a000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72b000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72c000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72d000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72e000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab72f000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab730000, 0xb57c4000, 4096)
V/AudioCache(  316): write(0xb57c4000, 4096)
V/AudioCache(  316): memcpy(0xab731000, 0xb57c4000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57c4000, 280)
V/AudioCache(  316): memcpy(0xab732000, 0xb57c4000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1432c40, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb1432c40, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): Pause Playback at 1068125
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1432c40, 8, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7196): close(31)
V/SoundPool( 7196): pointer = 0x9fe5b000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7196): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1453
I/UEI.SmartControl( 6801): Supports setup maps: true
,D/UEI.SmartControl( 6801): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6801): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6801): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6801): ### init IR Blaster...
D/serial_port( 6801): Configuring serial port
E/UEI.SmartControl( 6801): UEIBLaster setting for 616
I/UEI.SmartControl( 6801): Setting serial record hearder size = 2
I/UEI.SmartControl( 6801): configuring settings for MAXQ616
I/UEI.SmartControl( 6801): Get version...
D/UEI.SmartControl( 6801): serial port data available: 21
,D/UEI.SmartControl( 6801): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6801): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6801): QS saving settings...
,D/UEI.SmartControl( 6801): IR Blaster version: 25672567
,D/UEI.SmartControl( 6801): serial port data available: 4
,W/ContextImpl( 6801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6801): Services init done
D/UEI.SmartControl( 6801): QS Service init finished
D/UEI.SmartControl( 6801): QS Service version name: 2.1.91
D/UEI.SmartControl( 6801): QS Service version code: 201091
D/UEI.SmartControl( 6801): Service requested: Control
D/UEI.SmartControl( 6801): Internal service binding...
I/UEI.SmartControl( 6801): Device manager: loading config....
I/QRemote ( 7196): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6801): ----------- loading internal config...
I/UEI.SmartControl( 6801): ------ IControl API: 11
D/UEI.SmartControl( 6801): File observer start...
E/UEI.SmartControl( 6801): IR Port is disabled: false
D/UEI.SmartControl( 6801): Starting file observer...
I/UEI.SmartControl( 6801): Registering callback...
I/UEI.SmartControl( 6801): ------ IControl API: 19
I/UEI.SmartControl( 6801): Registering Services Ready callback...
,E/UEI.SmartControl( 6801): Loading SETTINGS...
D/UEI.SmartControl( 6801): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6801): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6801): -----service ready thread exits
I/QRemote ( 7196): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7196): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7196): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7196): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7196): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6801): ------ IControl API: 8
D/QRemote ( 7196): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7196): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7196): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7196): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7196): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7196): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7196): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7196): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7196): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7196): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452267316122]
D/QRemote ( 7196): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1034): Killing 6629:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 7196): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1034): failed to open /acct/uid_10023/pid_6629/cgroup.procs: No such file or directory
,V/QRemote ( 7196): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7196): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1034): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1034): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2645): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1034):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1034):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1034):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1034):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1034): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=270278  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=270294  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7196): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
,D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2645): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1034): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=270371  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=270371  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1034):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270371
E/WifiStateMachine( 1034):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270372
E/WifiStateMachine( 1034):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270372
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270372
E/WifiStateMachine( 1034):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270372
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=270372  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2645): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2645): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1034): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1034): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1034): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=270397  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=270398  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=270399  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1034):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=270400
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=270401
D/WifiNative-wlan0( 1034): doString: [STATUS]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1034):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1034): setVHTCapabilityType  : false
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1034): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1034): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7135): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7135): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7135): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7135): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : errorList=[]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UsbSettingsControl( 7135): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 7135): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7135): [AUTORUN] setTetherStatus() : status=false
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1034): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1034): Got NetworkAgent Messenger
,E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1034): NetworkAgent connected
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1034): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1034): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): WaitBeforeStartState
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270465  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270473  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270474  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270474  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1034):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 0
D/WifiNative-wlan0( 1034): SET ps 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5cfa5f6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5cfa5f6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1034): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1034): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1034):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1034):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateCOMPLETED
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2645): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1034): SET ps 1: returned true
,E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1034):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0,
E/WifiStateMachine( 1034): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1034): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1034): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{41c7c96 type 2 when 270638 com.google.android.gms} when 270638
V/WfdStateTracker( 2004): handleWifiStateChangedEvent: 1
,E/ConnectivityService( 1034): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1034): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine( 1034): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1034): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
D/ConnectivityService( 1034): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1034): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1034): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1034): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1034): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1034): currentScore = 0, newScore = 20
D/ConnectivityService( 1034):    accepting network in place of null
D/ConnectivityService( 1034): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1889): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1889):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1034): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1034): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1034): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1034): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1034): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1034): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1034): validation of new default Network = false
D/ConnectivityService( 1034): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1034): enableDataServiceNotify 
D/DSQN    ( 1034): start dsqn bin
V/NetworkPolicy( 1034): [LG_RESTRICTED] checkMobilePolicy_type()
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
,D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
W/dsqn    ( 7257): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7257): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7257): DSQN ssw
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7196): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7196): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7196): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7196): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7172): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7172): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7135): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7135): MCCMNC not supported: null
D/QRemote ( 7196): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7196): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7196): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7196): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7196): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1034): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1034): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1034): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7263): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7263): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7263): version 5.5.6 starting
E/dhcpcd  ( 7263): get_duid: m
D/dhcpcd  ( 7263): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7263): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7263): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7263): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7263): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7263): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7263): wlan0: sending REQUEST (xid 0x19628bcb), next in 3.90 seconds
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1034): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1034): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 15:35:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452267317475], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452267317445]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Validated
D/ConnectivityService( 1034): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WIFI    ( 1034): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1889): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1889):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/GCM     ( 2146): Connected
,D/GCM     ( 2146): Message class com.google.f.a.a.p
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1034): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5438): type=WIFI subType= reason=null isConnected=true
D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/Tethering( 1034): MasterInitialState.processMessage what=3
W/ContextImpl( 6576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5438): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1034): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7280 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7280): onCreate
,W/AppUp4:DB( 7280):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7280):  setFingerPrint start
I/AppUp4:DB( 7280):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7280):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7280):  SDK version = 21
I/AppUp4:DB( 7280):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7280): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7280): onReceive
,D/LgDataFeature( 7280): LgDataFeature() Constructor: none
,D/LgDataFeature( 7280): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7280): Context : android.app.ReceiverRestrictedContext@295a3da9
D/AppUp4:CustFacade( 7280): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7280): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7280): begin check event
I/AppUp4:CustModeStarterReceiver( 7280): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7280): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7280): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7280): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7280): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1034): Killing 6512:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10004/pid_6512/cgroup.procs: No such file or directory
,D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3362): DownloadService onCreate
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager( 1034): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7304 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@28d15bf2 on behalf of 3362
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@3a541243 on behalf of 3362
,D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@c95453e on behalf of 3362
V/DownloadManager( 3362): processing inserted download 1
V/DownloadManager( 3362): processing inserted download 4
V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
V/DownloadManager( 3362): processing inserted download 18
V/DownloadManager( 3362): processing inserted download 21
,V/DownloadManager( 3362): DownloadService onDestroy
W/ResourcesManager( 7304): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7304): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7304): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7304): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7304): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7304): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7304): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7304): LgDataFeature() Constructor: none
D/LgDataFeature( 7304): LgDataFeature() Constructor Done, null
,D/eas_req ( 7304): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1034): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7342 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  350): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 21.440ms
,I/HubEmail( 7304): JNI_OnLoad()
I/HubEmail( 7304): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7304): registerNatives()
I/HubEmail( 7304): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7304): registerNativeMethods()
I/HubEmail( 7304): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7304): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  350): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 17.960ms
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 17.810ms
,I/ActivityManager( 1034): Killing 6656:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1034):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7263): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
W/libprocessgroup( 1034): failed to open /acct/uid_10027/pid_6656/cgroup.procs: No such file or directory
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1034): identical MTU - not setting
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1034): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524295
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
I/dhcpcd  ( 7263): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7263): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7263): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7263): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7263): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7263): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7263): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7263): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1034): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7376 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1034): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7411 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6683:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1034): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1034): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1034): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1034): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1034): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1034): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1034): RunningState
W/libprocessgroup( 1034): failed to open /acct/uid_10061/pid_6683/cgroup.procs: No such file or directory
,I/ActivityManager( 1034): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7431 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6723:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7342): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7342): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1034): failed to open /acct/uid_10080/pid_6723/cgroup.procs: No such file or directory
,I/ActivityManager( 1034): Killing 6769:com.lge.eula/1000 (adj 15): empty #17
,I/art     ( 7431): Almond Protected OAT
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
,D/WeatherApplication( 7431): removeAccount
D/WeatherApplication( 7431): Account.length = 0
,E/WeatherApplication( 7431): OPERATOR:OPEN
D/WeatherAncestor( 7431): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:19
D/Weather.Utils( 7431): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7431): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7431): 2 : This is isUpdating : false
D/WeatherAncestor( 7431): connectivity changed - connection : true
D/WeatherService( 7431): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7431): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7431): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7431): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7431): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7431): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:19
,I/ActivityManager( 1034): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7450 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 6818:com.lge.bnr/1000 (adj 15): empty #17
E/WifiStateMachine( 1034):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1034):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6818/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7450): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7450): Loading: webviewchromium
I/LibraryLoader( 7450): Time to load native libraries: 4 ms (timestamps 3582-3586)
I/LibraryLoader( 7450): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7450): Binding Chromium to main looper Looper (main, tid 1) {2edfed78}
,I/LibraryLoader( 7450): Expected native library version number "",actual native library version number ""
I/chromium( 7450): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7450): Initializing chromium process, renderers=0
W/art     ( 7450): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  316): registerClient() client 0xb558a2a0, uid 10093
W/AudioManagerAndroid( 7450): Requires BLUETOOTH permission
W/chromium( 7450): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7450): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7450): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7450): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7450): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7450): Build Date: 12/12/14 금
I/Adreno-EGL( 7450): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7450): Remote Branch: 
I/Adreno-EGL( 7450): Local Patches: 
I/Adreno-EGL( 7450): Reconstruct Branch: 
,V/WifiInternetCheck( 1034): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5438): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 7450): Starting up...
I/ActivityManager( 1034): Killing 6849:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10005/pid_6849/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7280): onReceive
D/AppUp4:CustFacade( 7280): Context : android.app.ReceiverRestrictedContext@295a3da9
D/AppUp4:CustFacade( 7280): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7280): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7280): begin check event
I/AppUp4:CustModeStarterReceiver( 7280): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3362): DownloadService onCreate
,I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@15f8c8ec on behalf of 3362
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 3362): in trimDatabase
,V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@3eb386bb on behalf of 3362
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@151f87d8 on behalf of 3362
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3362): processing inserted download 1
I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3362): processing inserted download 4
V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
D/WeatherAncestor( 7431): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:20
V/DownloadManager( 3362): processing inserted download 18
D/Weather.Utils( 7431): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7431): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7431): 2 : This is isUpdating : false
D/WeatherAncestor( 7431): connectivity changed - connection : true
D/WeatherService( 7431): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29e90acf
V/DownloadManager( 3362): processing inserted download 21
D/ForecastDataCache( 7431): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7431): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7431): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7431): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7431): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:20
,V/DownloadManager( 3362): DownloadService onDestroy
I/art     ( 2146): Explicit concurrent mark sweep GC freed 38107(2MB) AllocSpace objects, 7(1008KB) LOS objects, 51% free, 30MB/62MB, paused 1.086ms total 44.799ms
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/Kids    ( 2363): [AccountUtils] Account not ready
W/Kids    ( 2363): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2363): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2363): 	at java.lang.Thread.run(Thread.java:818)
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
,V/FormManager( 7342): There are no updated forms. The schedule will be deleted.
,D/PostponalbeReceiver( 6576): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/ContextImpl( 6576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7280): [onReceive] request level :IDLE....
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,V/FormManager( 7342): Alarm would be updated, because LastCheckTime has been updated.
I/AppUp4:CustModeStarterReceiver( 7280): onReceive
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AppUp4:CustFacade( 7280): Context : android.app.ReceiverRestrictedContext@295a3da9
D/AppUp4:CustFacade( 7280): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7280): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7280): begin check event
I/AppUp4:CustModeStarterReceiver( 7280): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3362): DownloadService onCreate
,I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@1c32be16 on behalf of 3362
D/LGDMClient( 4299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/LGDMClient( 4299): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@20f14984 on behalf of 3362
W/Kids    ( 2363): [AccountUtils] Account not ready
W/Kids    ( 2363): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2363): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2363): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 1034): Explicit concurrent mark sweep GC freed 84368(3MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.666ms total 85.822ms
,V/DownloadManager( 3362): DownloadService onStartCommand
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
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
E/LGDMClient( 4299): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@a94a5a2 on behalf of 3362
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
,D/LGDMClient( 4299): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4299): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3362): processing inserted download 1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/DownloadManager( 3362): processing inserted download 4
V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
V/DownloadManager( 3362): processing inserted download 18
I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = true
D/PhoneState( 3300): setPdpRejectCasuse : false
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3362): processing inserted download 21
W/Settings( 7304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3362): DownloadService onDestroy
,D/WeatherAncestor( 7431): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:20
D/Weather.Utils( 7431): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7431): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7431): 2 : This is isUpdating : false
D/WeatherAncestor( 7431): connectivity changed - connection : true
D/WeatherService( 7431): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29e90acf
D/ForecastDataCache( 7431): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7431): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7431): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7431): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7431): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:35:20
V/FormManager( 7342): There are no updated forms. The schedule will be deleted.
V/FormManager( 7342): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/Kids    ( 2363): [AccountUtils] Account not ready
W/Kids    ( 2363): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2363): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2363): 	at java.lang.Thread.run(Thread.java:818)
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
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6801): Internal timer expired: 4
D/UEI.SmartControl( 6801): unbind internal service
,D/serial_port( 6801): close(fd = 24)
,I/UEI.SmartControl( 6801): Serial port is closed.
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1034): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7063): Test app app.js loaded
I/jxcore-log( 7063): 
,I/chromium( 7063): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7063): 
,I/chromium( 7063): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7063): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 277953767190; DSPS: 9248696; Offset : -4307174501
I/GAV4    ( 7450): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{38efbcbc type 2 when 297886 android} when 297886
,V/QRemote ( 7196): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7196): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1453
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 297960253745; DSPS: 9904269; Offset : -4307187851
I/BooksSync( 6949): Starting books sync
,D/BooksSync( 6949): started syncMyEbooks
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1624558547116852327&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1624558547116852327&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1624558547116852327&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
E/BooksSync( 6949): Soft error: 
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1624558547116852327&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
,E/BooksSync( 6949): Sync error
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1624558547116852327&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
I/BooksSync( 6949): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297886, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 7063): TAP version 13
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # multiplex can send data
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 1 String should be length:200
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,E/WifiStateMachine( 1034):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1034):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1034):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
I/jxcore-log( 7063): # basic
I/jxcore-log( 7063): 
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 317962807123; DSPS: 10559713; Offset : -4307197925
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 2 sane
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # another
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 3 sane
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{24cebcc6 type 2 when 327959 android} when 327959
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/jxcore-log( 7063): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 4 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 5 null
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 6 (unnamed assert)
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 7 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 8 should not throw
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 337965051021; DSPS: 11215146; Offset : -4307181680
,I/jxcore-log( 7063): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 9 (unnamed assert)
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 10 (unnamed assert)
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 11 should not throw
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 12 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 13 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 14 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # failed to get mobile documents path
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 15 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 357967141222; DSPS: 11870575; Offset : -4307197217
,I/jxcore-log( 7063): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 16 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 17 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 18 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # #init should register the networkChanged event
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6213): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6213): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6213): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6213): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6213): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6213): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6213): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6213): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/jxcore-log( 7063): ok 19 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #startBroadcasting should throw on null device name
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 377969471266; DSPS: 12526011; Offset : -4307186353
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 20 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 397971795425; DSPS: 13181447; Offset : -4307181686
,I/jxcore-log( 7063): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 21 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 22 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 23 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #startBroadcasting should throw on negative port
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 24 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 417973784324; DSPS: 13836872; Offset : -4307176481
,I/jxcore-log( 7063): # #startBroadcasting should throw on too large port
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 25 should throw
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 26 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 27 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 28 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7063): 
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 29 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 30 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 31 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 437976036556; DSPS: 14492306; Offset : -4307182447
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 457977987173; DSPS: 15147730; Offset : -4307185058
,I/jxcore-log( 7063): ok 32 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 33 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 34 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 35 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 36 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 37 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 38 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 477980908260; DSPS: 15803186; Offset : -4307193685
,I/jxcore-log( 7063): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 39 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 40 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{c7b1638 type 2 when 492521 android} when 492521
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/jxcore-log( 7063): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
I/jxcore-log( 7063): ok 41 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 42 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 497983007314; DSPS: 16458614; Offset : -4307169670
,I/jxcore-log( 7063): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): ok 43 should be equal
I/jxcore-log( 7063): 
I/jxcore-log( 7063): ok 44 should be equal
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # setup
I/jxcore-log( 7063): 
I/jxcore-log( 7063): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): # teardown
I/jxcore-log( 7063): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267557925.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267557925.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3806): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267557925.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267557925.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267557925.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267557925.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@43ce046e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@43ce046e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
,D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535373932352e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535373932352e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535373932351f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535373932351f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 2004): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
I/jxcore-log( 7063): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535373932351f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535373932351f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
,D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
I/jxcore-log( 7063): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/LGWifiP2pService( 1034): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558041.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558041.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558041.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558041.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558041.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558041.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dbd95982 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dbd95982 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383034312e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383034312e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383034311f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383034311f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
I/jxcore-log( 7063): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/LGWifiP2pService( 1034): discovery change broadcast true
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 7063): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383034311f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558090.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558090.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383034311f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558090.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558090.7063","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
D/LGWifiP2pService( 1034): InactiveState{ when=-25ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558090.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558090.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-32ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1034): P2pEnabledState{ when=-32ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-14ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-14ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
I/jxcore-log( 7063): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9ce7c8fa target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9ce7c8fa target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383039302e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 ,4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383039302e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383039301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/jxcore-log( 7063): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383039301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-3ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558136.7063,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558136.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
,D/LGWifiP2pService( 1034): InactiveState{ when=-12ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-12ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383039301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383039301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1034): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558136.7063
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558136.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558136.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558136.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3415038 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3415038 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383133362e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
I/jxcore-log( 7063): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383133362e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383133361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383133361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383133361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.t,haliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383133361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 7063): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558164.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558164.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558164.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558164.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558164.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558164.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ee2592f6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ee2592f6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383136342e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383136342e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383136341f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
,I/jxcore-log( 7063): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383136341f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383136341f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e2,23a22313435323236373535383136341f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
I/jxcore-log( 7063): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558188.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558188.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558188.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558188.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558188.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558188.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2e549b6a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2e549b6a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383138382e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383138382e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383138381f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383138381f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.t,haliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
,I/jxcore-log( 7063): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383138381f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383138381f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 7063): ok 56 Should be able to call stopBroadcasting without error,
I/jxcore-log( 7063): 
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1034): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558209.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558209.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558209.7063
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558209.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558209.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558209.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9bd2d0f6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9bd2d0f6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
,D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383230392e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383230392e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383230391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383230391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
I/jxcore-log( 7063): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063),: onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
,I/jxcore-log( 7063): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383230391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558230.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383230391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/LGWifiP2pService( 1034): InactiveState{ when=-3ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558230.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btcon,nectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558230.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558230.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558230.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558230.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fa011302 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fa011302 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383233302e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383233302e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383233301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383233301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
I/jxcore-log( 7063): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/or,g.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383233301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383233301f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
,I/jxcore-log( 7063): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558249.7063
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558249.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558249.7063
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558249.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558249.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558249.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d6ce97ee target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d6ce97ee target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
,D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383234392e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383234392e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383234391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383234391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 7063): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
,D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
D/LGWifiP2pService( 1034): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
,D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383234391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383234391f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
,D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 7063): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1034): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1034): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558266.7063
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): bind: Binding a new listener
D/LGWifiP2pService( 1034): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558266.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7063): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): start: OK
I/io.jxcore.node.ConnectionHelper( 7063): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452267558266.7063
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7063): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452267558266.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): start: {"pi":"58:3F:54:73:64:C0","pn":"1452267558266.7063","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452267558266.7063","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a479fb0 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a479fb0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState add service
D/LGWifiP2pService( 1034): add a new client
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383236362e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236373535383236362e37303633222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383236361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1034): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383236361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): start: OK
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2645): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 2004): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1034): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1034): P2P_FIND 120: returned true
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/LGWifiP2pService( 1034): discovery change broadcast true
I/jxcore-log( 7063): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7063): 
I/io.jxcore.node.ConnectionHelper( 7063): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7063): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7063): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7063): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7063): stop: Stopping services
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=,139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7063): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7063): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7063): setState: NOT_STARTED
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383236361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1034): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236373535383236361f37303633222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1034): remove client information from framework
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: P2P_STOP_FIND
I/jxcore-log( 7063): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7063): 
I/wpa_supplicant( 2645): P2P-FIND-STOPPED 
D/WfdsMonitor( 2004): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1034): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1034): P2P_STOP_FIND: returned true
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState clear service request
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): discovery change broadcast false
,I/jxcore-log( 7063): # setup,
I/jxcore-log( 7063): 
,I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7063): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7063): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7063): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7063): Service requests cleared successfully
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 517985250328; DSPS: 17114048; Offset : -4307185035
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 537987275164; DSPS: 17769474; Offset : -4307174385
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{28826ced type 2 when 552297 android} when 552297
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/BooksSync( 6949): Starting books sync
,D/BooksSync( 6949): started syncMyEbooks
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 37090(1969KB) AllocSpace objects, 10(928KB) LOS objects, 33% free, 44MB/66MB, paused 2.096ms total 120.168ms
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
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
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4385310095036241462&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4385310095036241462&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4385310095036241462&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
E/BooksSync( 6949): Soft error: 
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4385310095036241462&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
,E/BooksSync( 6949): Sync error
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4385310095036241462&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
I/BooksSync( 6949): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 552297, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 557989680208; DSPS: 18424913; Offset : -4307180021
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 577991997024; DSPS: 19080349; Offset : -4307182775
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{edec9e7 type 2 when 582415 android} when 582415
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 597994324620; DSPS: 19735785; Offset : -4307174411
,I/[SystemUI]LGPowerUI( 1473): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1473): On Skip Timer : true
,D/LEDHandler( 2004): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 2004): Battery Level Remaining: 100%
D/LEDHandler( 2004): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1473): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1473): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1034): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1473): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3806): Disconnected process message: 10, size: 0
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 617996716331; DSPS: 20391224; Offset : -4307193745
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 637998866375; DSPS: 21046654; Offset : -4307179801
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 658000965899; DSPS: 21702083; Offset : -4307185990
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 678003039537; DSPS: 22357511; Offset : -4307187652
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 698004945103; DSPS: 23012933; Offset : -4307173993
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 718006825668; DSPS: 23668355; Offset : -4307185622
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 738008650712; DSPS: 24323775; Offset : -4307191685
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 758011516434; DSPS: 24979229; Offset : -4307194563
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 778013720489; DSPS: 25634661; Offset : -4307187722
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 798015736367; DSPS: 26290087; Offset : -4307186082
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 818017803494; DSPS: 26945515; Offset : -4307194046
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 838020371091; DSPS: 27600959; Offset : -4307190160
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,I/ActivityManager( 1034): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7757 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7757): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7757): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c4c46e2
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
I/ActivityManager( 1034): Killing 6213:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10044/pid_6213/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 858022910146; DSPS: 28256402; Offset : -4307183882
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 878025144617; DSPS: 28911835; Offset : -4307177350
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 898027519870; DSPS: 29567273; Offset : -4307182365
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 918029493716; DSPS: 30222698; Offset : -4307192083
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 938031744490; DSPS: 30878131; Offset : -4307169041
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{60a8994 type 2 when 942520 com.android.bluetooth} when 942520
,W/bt-smp  ( 3806): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3806): Plain text(LSB ~ MSB) = 96 d4 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3806): Encrypted text(LSB ~ MSB) = 99 94 7a 21 93 77 e8 c2 c4 18 19 3f 27 e8 20 fe 
W/bt-btm  ( 3806): Stopping oneshot timer
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 958033570525; DSPS: 31533551; Offset : -4307174034
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 978035468954; DSPS: 32188973; Offset : -4307167773
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 998037517748; DSPS: 32844401; Offset : -4307194096
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1018039666387; DSPS: 33499831; Offset : -4307181740
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1038042014088; DSPS: 34155268; Offset : -4307183970
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{4dfdc3d type 2 when 1056949 android} when 1056949
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/BooksSync( 6949): Starting books sync
,D/BooksSync( 6949): started syncMyEbooks
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
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
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1058043380382; DSPS: 34810673; Offset : -4307189431
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
W/ApiaryClient( 6949): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2524009836897905615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2524009836897905615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2524009836897905615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
E/BooksSync( 6949): Soft error: 
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2524009836897905615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
,E/BooksSync( 6949): Sync error
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2524009836897905615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
I/BooksSync( 6949): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1056949, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1078045292406; DSPS: 35466095; Offset : -4307171111
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{2a0f68bf type 2 when 1087773 android} when 1087773
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1098047644168; DSPS: 36121532; Offset : -4307169255
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1118049782286; DSPS: 36776963; Offset : -4307197650
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1138051473998; DSPS: 37432378; Offset : -4307184483
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1158052895240; DSPS: 38087785; Offset : -4307197776
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1178055260805; DSPS: 38743222; Offset : -4307181778
,I/[SystemUI]LGPowerUI( 1473): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1473): On Skip Timer : true
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1034): battery changed pluggedType: 2
D/HeadsetStateMachine( 3806): Disconnected process message: 10, size: 0
D/LEDHandler( 2004): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 2004): Battery Level Remaining: 100%
D/LEDHandler( 2004): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1473): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1473): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1473): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1198056975537; DSPS: 39398638; Offset : -4307176187
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1218059236049; DSPS: 40054072; Offset : -4307173950
,I/UsageStatsService( 1034): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1238062064116; DSPS: 40709525; Offset : -4307184018
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1258064267181; DSPS: 41364957; Offset : -4307178165
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1278066124100; DSPS: 42020378; Offset : -4307182923
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1298068254561; DSPS: 42675808; Offset : -4307188640
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1318071753824; DSPS: 43331282; Offset : -4307168251
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
,I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1338074098192; DSPS: 43986719; Offset : -4307173789
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1358076376517; DSPS: 44642154; Offset : -4307184282
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1378078399791; DSPS: 45297580; Offset : -4307175142
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1398080557805; DSPS: 45953011; Offset : -4307183903
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1418082766078; DSPS: 46608443; Offset : -4307172817
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1438084900237; DSPS: 47263873; Offset : -4307174940
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1458086889396; DSPS: 47919298; Offset : -4307169503
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1478089107617; DSPS: 48574731; Offset : -4307179090
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1498091507194; DSPS: 49230170; Offset : -4307190324
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
,I/[SystemUI]Clock( 1473): called onTimeUpdated()
I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1518093742394; DSPS: 49885603; Offset : -4307182855
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1538095999886; DSPS: 50541037; Offset : -4307183820
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1558097944514; DSPS: 51196461; Offset : -4307192317
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1578100392267; DSPS: 51851901; Offset : -4307185814
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1598102547623; DSPS: 52507332; Offset : -4307197206
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1618104676210; DSPS: 53162761; Offset : -4307174489
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1638106873077; DSPS: 53818193; Offset : -4307174704
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1658108995413; DSPS: 54473623; Offset : -4307188730
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1678111787646; DSPS: 55129074; Offset : -4307173595
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1698114018211; DSPS: 55784507; Offset : -4307170736
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1718115947318; DSPS: 56439930; Offset : -4307164236
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1738117849601; DSPS: 57095353; Offset : -4307184586
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7757): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7757): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c4c46e2
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1758119980010; DSPS: 57750783; Offset : -4307190486
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1778122257816; DSPS: 58406217; Offset : -4307170799
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1798124135152; DSPS: 59061639; Offset : -4307185605
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
,I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1818126400405; DSPS: 59717073; Offset : -4307178757
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{200ef2d5 type 0 when 1452267991729 com.google.android.gms} when 1452267991729
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{1a187aea type 2 when 1171187 com.google.android.gms} when 1171187
I/ProcessStatsService( 1034): Prepared write state in 9ms
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,I/ProcessStatsService( 1034): Prepared write state in 11ms
,I/ProcessStatsService( 1034): Prepared write state in 13ms
,I/ProcessStatsService( 1034): Prepared write state in 12ms
,I/ProcessStatsService( 1034): Pruning old procstats: /data/system/procstats/state-2016-01-07-14-43-48.bin
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/EventLogService( 2363): Aggregate from 1452266191660 (log), 1452266191660 (data)
,D/GCM     ( 2146): Message class com.google.f.a.a.i
,I/GoogleURLConnFactory( 2146): Using platform SSLCertificateSocketFactory
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1838128700761; DSPS: 60372509; Offset : -4307197580
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{3db9ffaf type 2 when 1842544 com.android.bluetooth} when 1842544
,W/bt-smp  ( 3806): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3806): Plain text(LSB ~ MSB) = 92 99 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3806): Encrypted text(LSB ~ MSB) = 58 b0 86 a0 40 fc c4 b3 92 a6 de 59 d0 00 11 d1 
W/bt-btm  ( 3806): Stopping oneshot timer
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1858131530546; DSPS: 61027961; Offset : -4307175334
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,D/LocationManagerService( 1034): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2146): Explicit concurrent mark sweep GC freed 40118(2MB) AllocSpace objects, 31(4MB) LOS objects, 51% free, 30MB/62MB, paused 1.428ms total 46.310ms
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1878133616320; DSPS: 61683390; Offset : -4307195299
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1898135366676; DSPS: 62338807; Offset : -4307184497
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1918137538751; DSPS: 62994238; Offset : -4307179222
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1938139487338; DSPS: 63649662; Offset : -4307183812
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1958142329049; DSPS: 64305115; Offset : -4307180106
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1978144247687; DSPS: 64960538; Offset : -4307184206
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1998146156169; DSPS: 65615961; Offset : -4307198384
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 2018148412099; DSPS: 66271394; Offset : -4307170236
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 2038150310790; DSPS: 66926817; Offset : -4307194101
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 2058152673855; DSPS: 67582254; Offset : -4307180967
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=858184249, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{3ff27fb5 type 2 when 2062797 android} when 2062797
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=858184249 [*alarm*], flags=0x0
,I/BooksSync( 6949): Starting books sync
D/BooksSync( 6949): started syncMyEbooks
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1034): Explicit concurrent mark sweep GC freed 43609(2MB) AllocSpace objects, 17(1184KB) LOS objects, 33% free, 44MB/66MB, paused 1.927ms total 101.439ms
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1920052968665511887&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1920052968665511887&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2146): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2146): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2146): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2146): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2146): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2146): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2146): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2146): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2146): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2146): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6949): Authentication error
E/BooksAccountManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6949): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2e0d731 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6949): Error response from books API: {
W/ApiaryClient( 6949):  "error": {
W/ApiaryClient( 6949):   "errors": [
W/ApiaryClient( 6949):    {
W/ApiaryClient( 6949):     "domain": "global",
W/ApiaryClient( 6949):     "reason": "required",
W/ApiaryClient( 6949):     "message": "Login Required",
W/ApiaryClient( 6949):     "locationType": "header",
W/ApiaryClient( 6949):     "location": "Authorization"
W/ApiaryClient( 6949):    }
W/ApiaryClient( 6949):   ],
W/ApiaryClient( 6949):   "code": 401,
W/ApiaryClient( 6949):   "message": "Login Required"
W/ApiaryClient( 6949):  }
W/ApiaryClient( 6949): }
,W/ApiaryClient( 6949): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1920052968665511887&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6949): Headers:
W/ApiaryClient( 6949): accept-encoding: [gzip]
W/ApiaryClient( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6949): gdata-version: 2
E/BooksSync( 6949): Soft error: 
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1920052968665511887&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
,E/BooksSync( 6949): Sync error
E/BooksSync( 6949): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6949): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1920052968665511887&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6949): Headers:
E/BooksSync( 6949): accept-encoding: [gzip]
E/BooksSync( 6949): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6949): gdata-version: 2
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6949): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6949): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6949): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6949): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6949): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6949): {
E/BooksSync( 6949):  "error": {
E/BooksSync( 6949):   "errors": [
E/BooksSync( 6949):    {
E/BooksSync( 6949):     "domain": "global",
E/BooksSync( 6949):     "reason": "required",
E/BooksSync( 6949):     "message": "Login Required",
E/BooksSync( 6949):     "locationType": "header",
E/BooksSync( 6949):     "location": "Authorization"
E/BooksSync( 6949):    }
E/BooksSync( 6949):   ],
E/BooksSync( 6949):   "code": 401,
E/BooksSync( 6949):   "message": "Login Required"
E/BooksSync( 6949):  }
E/BooksSync( 6949): }
E/BooksSync( 6949): 
E/BooksSync( 6949): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6949): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6949): 	... 8 more
I/BooksSync( 6949): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2062797, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 2078155008482; DSPS: 68237690; Offset : -4307165781
,TIME-OUT KILL (timeout was 1800000ms)
```
