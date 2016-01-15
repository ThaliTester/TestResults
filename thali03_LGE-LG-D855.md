#### Test 561510938d3c4f5_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 277671096395; DSPS: 9239561; Offset : -4309838548
,D/AndroidRuntime( 7149): 
D/AndroidRuntime( 7149): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7149): CheckJNI is OFF
D/AndroidRuntime( 7149): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1978): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{cc9a99d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{cc9a99d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  330): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7168 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7149): Shutting down VM
V/ActivityManager( 1035): Display changed displayId=0
D/DSDPConnection( 1871): Display #0 changed.
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{2f372e57 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{18e76d44 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7168): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7168): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7168): Loading: webviewchromium
,I/LibraryLoader( 7168): Time to load native libraries: 4 ms (timestamps 7124-7128)
I/LibraryLoader( 7168): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7168): Binding Chromium to main looper Looper (main, tid 1) {2d7403c7}
I/LibraryLoader( 7168): Expected native library version number "",actual native library version number ""
I/chromium( 7168): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7168): Initializing chromium process, renderers=0
W/art     ( 7168): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7168): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7168): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
V/AudioPolicyService(  315): registerClient() client 0xb57eac20, uid 10311
I/chromium( 7168): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24d5713f:true
I/Adreno-EGL( 7168): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7168): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7168): Build Date: 12/12/14 금
I/Adreno-EGL( 7168): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7168): Remote Branch: 
I/Adreno-EGL( 7168): Local Patches: 
I/Adreno-EGL( 7168): Reconstruct Branch: 
,W/chromium( 7168): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7168): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7168): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7168): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7168): CordovaWebView is running on device made by: LGE
,W/art     ( 7168): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7168): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7168): Render dirty regions requested: true
I/OpenGLRenderer( 7168): Initialized EGL, version 1.4
D/OpenGLRenderer( 7168): Enabling debug mode 0
,W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{2ff93e12 u0 com.test.thalitest/.MainActivity t4}
,D/Atlas   ( 7168): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{f0d2b41 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7168): LgDataFeature() Constructor: none
D/LgDataFeature( 7168): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1475): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1475): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1475):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1475): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@dee8014,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +634ms (total +733ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{2ff93e12 u0 com.test.thalitest/.MainActivity t4} time:287554
,I/Timeline( 7168): Timeline: Activity_idle id: android.os.BinderProxy@289f6cb7 time:287557
I/chromium( 7168): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7168): 
,D/JsMessageQueue( 7168): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7168): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7168): 
,D/jxcore_app_log( 7168): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434846464
,D/JX-Cordova( 7168): jxcore cordova android initializing
E/GBMv2   (  330): DFP En is all cleared set to be enabled
E/GBMv2   (  330): Set value is all cleared set the max
I/GBMv2   (  330): DFP Enabled. Ignore VFP set
W/jxcore-log( 7168): Initializing JXcore engine
W/jxcore-log( 7168): JXcore engine is ready
W/jxcore-log( 7168): Starting JXcore engine
W/.test.thalitest( 7168): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6095]" dev="sockfs" ino=6095 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7168): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7168): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7639]" dev="sockfs" ino=7639 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7168): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7168): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34198]" dev="sockfs" ino=34198 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7168): Background sticky concurrent mark sweep GC freed 132262(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.662ms total 138.787ms
,W/jxcore-log( 7168): Platform android
W/jxcore-log( 7168): 
W/jxcore-log( 7168): Process ARCH arm
W/jxcore-log( 7168): 
I/jxcore-log( 7168): JXcore Cordova bridge is ready!
I/jxcore-log( 7168): 
W/jxcore-log( 7168): JXcore engine is started
,I/jxcore-log( 7168): Toggling radios to true
I/jxcore-log( 7168): 
,D/BluetoothAdapter( 7168): enable(): BT is already enabled..!
D/WifiService( 1035): New client listening to asynchronous messages
D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=7168, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1035): setWifiEnabled: true pid=7168, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1035): disconnect pid=7168, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1035): reconnect pid=7168, uid=10311, packageName=com.test.thalitest
E/WifiNative: ( 1035): [290,087,955 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
I/jxcore-log( 7168): Radios toggled
I/jxcore-log( 7168): 
,I/jxcore-log( 7168): My device name is: LGE-LG-D855
I/jxcore-log( 7168): 
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/Tethering( 1035): InitialState.processMessage what=4
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035): DISCONNECT: returned true
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
,I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7257 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/DhcpStateMachine( 1035): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2141): Read error: ssl=0xaa6d9c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaa6d9c00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1035): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1035):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1035): [290,254,684 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): ignoring duplicate network state non-change
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,V/WfdStateTracker( 1978): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1035): hidePasspointNotification off =false
D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1035): RECONNECT: returned true
E/WifiStateMachine( 1035):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1035): hidePasspointNotification off =false
E/WifiStateMachine( 1035):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290283
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1035):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290291
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1035): hidePasspointNotification off =false
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=290333  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=290333  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=290336  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20( 1035): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityManager.CallbackHandler( 1475): CM callback handler got msg 524292
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=290342  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Connecti,vityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1035): Removing idletimer
D/TelephonyNetworkFactory-1( 1871): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
,V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ResourcesManager( 7257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7257): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1475): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/Ads     ( 2334): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
D/TelephonyIcons( 1475): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7257): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7257): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7257): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6567:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10004/pid_6567/cgroup.procs: No such file or directory
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7257): LgDataFeature() Constructor: none
D/LgDataFeature( 7257): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
,I/ActivityManager( 1035): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7319 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1035): Killing 6681:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/art     (  370): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 20.960ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 19.517ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 19.109ms
,W/libprocessgroup( 1035): failed to open /acct/uid_10008/pid_6681/cgroup.procs: No such file or directory
,W/ResourcesManager( 7319): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7319): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7319): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7319): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7319): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7319): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7319): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7319): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7319): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7319): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7319): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7319): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7319): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7319): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7319): LgDataFeature() Constructor: none
D/LgDataFeature( 7319): LgDataFeature() Constructor Done, null
,V/SoundPool( 7319): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7319): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7319): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7319): doLoad: loading sample sampleID=1
V/SoundPool( 7319): Start decode
V/MediaPlayer[Native]( 7319): decode(31, 10857164, 17813)
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
I/QRemote ( 7319): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6900): QS Service created
D/QRemote ( 7319): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7319): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7319): Create singleton instance
I/UEI.SmartControl( 6900): Service initServices...
D/UEI.SmartControl( 6900): QS start get config
V/LGParserOSAL(  315): supported mime: application/ogg
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
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
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
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output por,t
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcd30 on output port
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
V/AudioCache(  315): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb54749c0, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797104
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcfb0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab602000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab603000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab604000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab605000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab606000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab607000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab608000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab609000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60a000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60b000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60c000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60d000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60e000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab60f000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab610000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab611000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab612000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab613000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab614000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab615000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab616000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab617000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab618000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab619000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61a000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61b000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61c000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61d000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61e000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab61f000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab620000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab621000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab622000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab623000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab624000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab625000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab626000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab627000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab628000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab629000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62a000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62b000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62c000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62d000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62e000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab62f000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab630000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab631000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab632000, 0xb57c1000, 4096)
V/AudioCache(  315): write(0xb57c1000, 4096)
V/AudioCache(  315): memcpy(0xab633000, 0xb57c1000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb57c1000, 280)
V/AudioCache(  315): memcpy(0xab634000, 0xb57c1000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): Pause Playback at 1068125
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb54749c0, 8, 0, 0)
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
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcfb0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
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
V/SoundPool( 7319): close(31)
V/SoundPool( 7319): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7319): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9281
,I/UEI.SmartControl( 6900): Supports setup maps: true
,D/UEI.SmartControl( 6900): QS start statue = true Error code = 0
I/UEI.SmartControl( 6900): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6900): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6900): ### init IR Blaster...
D/serial_port( 6900): Configuring serial port
E/UEI.SmartControl( 6900): UEIBLaster setting for 616
I/UEI.SmartControl( 6900): Setting serial record hearder size = 2
I/UEI.SmartControl( 6900): configuring settings for MAXQ616
I/UEI.SmartControl( 6900): Get version...
D/UEI.SmartControl( 6900): serial port data available: 21
,D/UEI.SmartControl( 6900): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6900): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6900): QS saving settings...
D/UEI.SmartControl( 6900): IR Blaster version: 25672567
D/UEI.SmartControl( 6900): serial port data available: 4
,W/ContextImpl( 6900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6900): Services init done
D/UEI.SmartControl( 6900): QS Service init finished
D/UEI.SmartControl( 6900): QS Service version name: 2.1.91
D/UEI.SmartControl( 6900): QS Service version code: 201091
D/UEI.SmartControl( 6900): Service requested: Control
I/UEI.SmartControl( 6900): Device manager: loading config....
D/UEI.SmartControl( 6900): ----------- loading internal config...
I/QRemote ( 7319): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6900): Internal service binding...
I/UEI.SmartControl( 6900): ------ IControl API: 11
D/UEI.SmartControl( 6900): File observer start...
E/UEI.SmartControl( 6900): IR Port is disabled: false
D/UEI.SmartControl( 6900): Starting file observer...
I/UEI.SmartControl( 6900): Registering callback...
I/UEI.SmartControl( 6900): ------ IControl API: 19
I/UEI.SmartControl( 6900): Registering Services Ready callback...
E/UEI.SmartControl( 6900): Loading SETTINGS...
,D/UEI.SmartControl( 6900): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6900): Notify AllClients services are ready: 0
,I/QRemote ( 7319): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7319): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7319): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7319): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7319): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6900): ------ IControl API: 8
D/UEI.SmartControl( 6900): -----service ready thread exits
D/QRemote ( 7319): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7319): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7319): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7319): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7319): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7319): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7319): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7319): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7319): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7319): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452860636958]
D/QRemote ( 7319): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1035): Killing 6703:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/QRemote ( 7319): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6703/cgroup.procs: No such file or directory
,V/QRemote ( 7319): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7319): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2661): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
,E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=292472  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=292487  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2661): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292573  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=292574  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292574
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292574
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292575
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292575
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=292576
,I/wpa_supplicant( 2661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7257): [AUTORUN] getUsbConnected() : connected=true
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : activeList=[]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7257): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsControl( 7257): [AUTORUN] setTetherStatus() : status=false
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292587  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=292601  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292604  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=292605  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292606
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=292606
D/WifiNative-wlan0( 1035): doString: [STATUS]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
,D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1035): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1035): Start Dhcp Watchdog 2
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1035): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=292651  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292653  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292653  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=292654  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d8c3c78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d8c3c78 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper( 1035): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1035): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1035): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1978): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1035): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{,20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1475): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1475): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
,D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1475): CM callback handler got msg 524290
W/dsqn    ( 7398): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7398): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7398): DSQN ssw
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1475): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7319): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7319): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7319): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7319): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
,D/QRemote ( 7319): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7319): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7319): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7319): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7319): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  311): argv[0]=dsqncommand
,D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1035): start to monitor internet connection
D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7404): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7404): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7404): version 5.5.6 starting
E/dhcpcd  ( 7404): get_duid: m
D/dhcpcd  ( 7404): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7404): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 12:23:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452860637909], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452860637887]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Validated
D/ConnectivityService( 1035): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1871): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1475): CM callback handler got msg 524290
,D/TelephonyIcons( 1475): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1475): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{8f4afb8 type 2 when 292904 com.google.android.gms} when 292904
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,D/dhcpcd  ( 7404): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7404): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7404): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7404): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7404): wlan0: sending REQUEST (xid 0xe34c4d8a), next in 3.44 seconds
,I/Choreographer( 7168): Skipped 191 frames!  The application may be doing too much work on its main thread.
,D/GCM     ( 2141): Connected
,I/chromium( 7168): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7168): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/GCM     ( 2141): Message class com.google.f.a.a.p
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5496): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5496): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7426 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7426): onCreate
W/AppUp4:DB( 7426):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7426):  setFingerPrint start
I/AppUp4:DB( 7426):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7426):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7426):  SDK version = 21
I/AppUp4:DB( 7426):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7426): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] BroadcastReceiver onReceive,
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7426): onReceive
D/LgDataFeature( 7426): LgDataFeature() Constructor: none
D/LgDataFeature( 7426): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7426): Context : android.app.ReceiverRestrictedContext@34a5591d
D/AppUp4:CustFacade( 7426): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7426): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7426): begin check event
I/AppUp4:CustModeStarterReceiver( 7426): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7426): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7426): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7426): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7426): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1035): Killing 6731:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_6731/cgroup.procs: No such file or directory
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3368): DownloadService onCreate
,I/DownloadManager( 3368): in removeSpuriousFiles
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@376cbe31 on behalf of 3368
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
,V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@6261916 on behalf of 3368
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3368): DownloadService onStartCommand
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@3a1e0c6d on behalf of 3368
,D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/eas_req ( 6758): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
V/DownloadManager( 3368): processing inserted download 7
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
,V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
V/DownloadManager( 3368): processing inserted download 21
V/DownloadManager( 3368): DownloadService onDestroy
I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7472 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6758): JNI_OnLoad()
I/HubEmail( 6758): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6758): registerNatives()
I/HubEmail( 6758): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6758): registerNativeMethods()
I/HubEmail( 6758): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6758): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3336): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3336): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3336): networkInfo.isConnected() = false
,I/ActivityManager( 1035): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7495 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 7404): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
I/dhcpcd  ( 7404): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7404): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7404): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7404): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7404): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7404): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7404): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7404): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1035):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1035): identical MTU - not setting
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1475): CM callback handler got msg 524295
V/FormManager( 7472): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7472): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7533 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6785:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_6785/cgroup.procs: No such file or directory
,I/ActivityManager( 1035): Killing 6816:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
,V/LgDhcpStateMachineHelper( 1035): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7559 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6853:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6816/cgroup.procs: No such file or directory
,W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_6853/cgroup.procs: No such file or directory
I/art     ( 7559): Almond Protected OAT
,D/WeatherApplication( 7559): removeAccount
,D/WeatherApplication( 7559): Account.length = 0
E/WeatherApplication( 7559): OPERATOR:OPEN
D/WeatherAncestor( 7559): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:23:59
D/Weather.Utils( 7559): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7559): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7559): 2 : This is isUpdating : false
,D/WeatherAncestor( 7559): connectivity changed - connection : true
D/WeatherService( 7559): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7559): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7559): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7559): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7559): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7559): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:23:59
,I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7583 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6923:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6923/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7583): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7583): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
I/WebViewFactory( 7583): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7583): Loading: webviewchromium
I/LibraryLoader( 7583): Time to load native libraries: 6 ms (timestamps 5249-5255)
I/LibraryLoader( 7583): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7583): Binding Chromium to main looper Looper (main, tid 1) {3a87ebbc}
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/LibraryLoader( 7583): Expected native library version number "",actual native library version number ""
I/chromium( 7583): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7583): Initializing chromium process, renderers=0
W/art     ( 7583): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7583): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7583): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7583): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb14fd6a0, uid 10093
W/AudioManagerAndroid( 7583): Requires BLUETOOTH permission
I/Adreno-EGL( 7583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7583): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7583): Build Date: 12/12/14 금
I/Adreno-EGL( 7583): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7583): Remote Branch: 
I/Adreno-EGL( 7583): Local Patches: 
I/Adreno-EGL( 7583): Reconstruct Branch: 
I/NSApplication( 7583): Starting up...
I/ActivityManager( 1035): Killing 6945:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6945/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7426): onReceive
D/AppUp4:CustFacade( 7426): Context : android.app.ReceiverRestrictedContext@34a5591d
D/AppUp4:CustFacade( 7426): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7426): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7426): begin check event
I/AppUp4:CustModeStarterReceiver( 7426): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3368): DownloadService onCreate
I/DownloadManager( 3368): in removeSpuriousFiles
V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@34a2c133 on behalf of 3368
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
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@209bfcf0 on behalf of 3368
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7472): There are no updated forms. The schedule will be deleted.
V/FormManager( 7472): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1035): Explicit concurrent mark sweep GC freed 80653(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.771ms total 129.542ms
V/DownloadManager( 3368): DownloadService onStartCommand
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/Tethering( 1035): MasterInitialState.processMessage what=3
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@43e3d8f on behalf of 3368
I/NetworkMonitor( 5496): type=WIFI subType= reason=null isConnected=true
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
V/DownloadManager( 3368): processing inserted download 7
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/LgeMiscReceiver( 3336): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3336): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3336): networkInfo.isConnected() = false
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3368): processing inserted download 18
V/DownloadManager( 3368): processing inserted download 21
D/WeatherAncestor( 7559): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:24:0
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Weather.Utils( 7559): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7559): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7559): 2 : This is isUpdating : false
V/DownloadManager( 3368): DownloadService onDestroy
D/WeatherAncestor( 7559): connectivity changed - connection : true
D/WeatherService( 7559): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a31563
W/Kids    ( 2334): [AccountUtils] Account not ready
W/Kids    ( 2334): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2334): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2334): 	at java.lang.Thread.run(Thread.java:818)
D/ForecastDataCache( 7559): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7559): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7559): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7559): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7559): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:24:0
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
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6650): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7426): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7426): onReceive
,D/AppUp4:CustFacade( 7426): Context : android.app.ReceiverRestrictedContext@34a5591d
D/AppUp4:CustFacade( 7426): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7426): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7426): begin check event
I/AppUp4:CustModeStarterReceiver( 7426): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3368): DownloadService onCreate
I/DownloadManager( 3368): in removeSpuriousFiles
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@14e95c25 on behalf of 3368
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
,I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@2b0db1fa on behalf of 3368
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3368): DownloadService onStartCommand
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@d7895a1 on behalf of 3368
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
I/LgeMiscReceiver( 3336): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3336): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3336): networkInfo.isConnected() = true
D/PhoneState( 3336): setPdpRejectCasuse : false
V/DownloadManager( 3368): processing inserted download 7
V/DownloadManager( 3368): processing inserted download 8
,V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
V/DownloadManager( 3368): processing inserted download 21
D/WeatherAncestor( 7559): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:24:1
V/DownloadManager( 3368): DownloadService onDestroy
D/Weather.Utils( 7559): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7559): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7559): 2 : This is isUpdating : false
D/WeatherAncestor( 7559): connectivity changed - connection : true
D/WeatherService( 7559): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a31563
D/ForecastDataCache( 7559): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7559): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7559): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7559): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7559): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:24:1
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
W/Kids    ( 2334): [AccountUtils] Account not ready
W/Kids    ( 2334): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2334): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2334): 	at java.lang.Thread.run(Thread.java:818)
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
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
,D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/Kids    ( 2334): [AccountUtils] Account not ready
W/Kids    ( 2334): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2334): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2334): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/QRemote ( 7319): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7319): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9281
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,D/UEI.SmartControl( 6900): Internal timer expired: 4
D/UEI.SmartControl( 6900): unbind internal service
,V/FormManager( 7472): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7472): Alarm would be updated, because LastCheckTime has been updated.
D/serial_port( 6900): close(fd = 24)
,I/UEI.SmartControl( 6900): Serial port is closed.
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1035): isHttpConnectionAvailable - We got a valid response : 204
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 297672445875; DSPS: 9894965; Offset : -4309831867
,I/GAV4    ( 7583): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{50cbfec type 2 when 302067 android} when 302067
,I/BooksSync( 7035): Starting books sync
,D/BooksSync( 7035): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/HttpHelper( 7035): null auth token
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782455296194532209&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782455296194532209&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782455296194532209&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
,E/BooksSync( 7035): Soft error: 
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782455296194532209&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
E/BooksSync( 7035): Sync error
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3782455296194532209&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
I/BooksSync( 7035): Finished books sync
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302067, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 317674352845; DSPS: 10550387; Offset : -4309816857
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{13c44c02 type 2 when 332121 android} when 332121
,E/WifiStateMachine( 1035):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 337675962995; DSPS: 11205800; Offset : -4309824217
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
,I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 357677537362; DSPS: 11861211; Offset : -4309806350
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6235): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6235): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6235): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6235): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6235): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6235): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 377679168031; DSPS: 12516625; Offset : -4309823396
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 397681264743; DSPS: 13172054; Offset : -4309832605
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 417682899631; DSPS: 13827467; Offset : -4309815097
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 437684508893; DSPS: 14482880; Offset : -4309823294
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 457686028834; DSPS: 15138290; Offset : -4309829178
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 477688010128; DSPS: 15793715; Offset : -4309831631
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 497689548193; DSPS: 16449125; Offset : -4309819419
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 517691421155; DSPS: 17104547; Offset : -4309838652
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 537692989427; DSPS: 17759958; Offset : -4309826619
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 557694521556; DSPS: 18415368; Offset : -4309820473
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{18ae9b14 type 2 when 561800 android} when 561800
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,I/BooksSync( 7035): Starting books sync
,D/BooksSync( 7035): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3561631372869137618&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 30210(1351KB) AllocSpace objects, 10(1184KB) LOS objects, 33% free, 44MB/66MB, paused 2.989ms total 155.154ms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3561631372869137618&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3561631372869137618&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
,E/BooksSync( 7035): Soft error: 
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3561631372869137618&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
E/BooksSync( 7035): Sync error
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3561631372869137618&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
,I/BooksSync( 7035): Finished books sync
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 561800, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 577696420819; DSPS: 19070790; Offset : -4309813352
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{272945e type 2 when 591984 android} when 591984
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 597697998729; DSPS: 19726202; Offset : -4309822461
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 617699539918; DSPS: 20381613; Offset : -4309837669
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 637701994755; DSPS: 21037053; Offset : -4309824055
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,I/ActivityManager( 1035): Killing 6971:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10005/pid_6971/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,I/ActivityManager( 1035): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7782 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7782): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7782): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2783d106
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
I/ActivityManager( 1035): Killing 6235:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10044/pid_6235/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 657703580008; DSPS: 21692465; Offset : -4309825612
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 677705020573; DSPS: 22347872; Offset : -4309819477
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 697706548845; DSPS: 23003282; Offset : -4309817136
,I/[SystemUI]LGPowerUI( 1475): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1475): On Skip Timer : true
D/WifiController( 1035): battery changed pluggedType: 2
D/LEDHandler( 1978): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1978): Battery Level Remaining: 100%
D/LEDHandler( 1978): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1475): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1475): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1475): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3830): Disconnected process message: 10, size: 0
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 717708424724; DSPS: 23658704; Offset : -4309833191
I/[SystemUI]LGPowerUI( 1475): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1475): On Skip Timer : true
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1035): battery changed pluggedType: 2
D/HeadsetStateMachine( 3830): Disconnected process message: 10, size: 0
D/LEDHandler( 1978): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1978): Battery Level Remaining: 100%
D/LEDHandler( 1978): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1475): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1475): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1475): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 737710708519; DSPS: 24314138; Offset : -4309807775
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 757712237261; DSPS: 24969549; Offset : -4309835351
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 777713848868; DSPS: 25624961; Offset : -4309810762
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 797715613756; DSPS: 26280379; Offset : -4309815946
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 817717161613; DSPS: 26935790; Offset : -4309824408
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 837718739366; DSPS: 27591202; Offset : -4309833490
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 857720929984; DSPS: 28246633; Offset : -4309809672
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 877722479611; DSPS: 28902044; Offset : -4309816546
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 897724055333; DSPS: 29557456; Offset : -4309827582
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 917725605117; DSPS: 30212867; Offset : -4309834272
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 937727561567; DSPS: 30868291; Offset : -4309830843
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,W/bt-smp  ( 3830): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3830): Plain text(LSB ~ MSB) = e5 9e 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3830): Encrypted text(LSB ~ MSB) = 03 05 c8 d9 2a 34 d0 0a c2 93 0e 6e 55 93 b0 3b 
,W/bt-btm  ( 3830): Stopping oneshot timer
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{12b2003f type 2 when 942564 com.android.bluetooth} when 942564
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 957729415361; DSPS: 31523711; Offset : -4309808260
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 977731606709; DSPS: 32179143; Offset : -4309814048
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 997733146908; DSPS: 32834554; Offset : -4309830245
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1017735102474; DSPS: 33489978; Offset : -4309827961
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1037736678821; DSPS: 34145390; Offset : -4309838502
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1057738217355; DSPS: 34800800; Offset : -4309825899
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{21977d0c type 2 when 1077420 android} when 1077420
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1077740320473; DSPS: 35456229; Offset : -4309826957
,I/BooksSync( 7035): Starting books sync
,D/BooksSync( 7035): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
,W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4495598213284141498&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
,W/ApiaryClient( 7035): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4495598213284141498&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2141): Explicit concurrent mark sweep GC freed 44241(2MB) AllocSpace objects, 27(3MB) LOS objects, 51% free, 30MB/62MB, paused 1.993ms total 61.857ms
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4495598213284141498&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
,E/BooksSync( 7035): Soft error: 
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4495598213284141498&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
E/BooksSync( 7035): Sync error
E/BooksSync( 7035): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4495598213284141498&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7035): Headers:
E/BooksSync( 7035): accept-encoding: [gzip]
E/BooksSync( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7035): gdata-version: 2
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7035): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7035): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7035): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7035): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7035): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7035): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7035): {
E/BooksSync( 7035):  "error": {
E/BooksSync( 7035):   "errors": [
E/BooksSync( 7035):    {
E/BooksSync( 7035):     "domain": "global",
E/BooksSync( 7035):     "reason": "required",
E/BooksSync( 7035):     "message": "Login Required",
E/BooksSync( 7035):     "locationType": "header",
E/BooksSync( 7035):     "location": "Authorization"
E/BooksSync( 7035):    }
E/BooksSync( 7035):   ],
E/BooksSync( 7035):   "code": 401,
E/BooksSync( 7035):   "message": "Login Required"
E/BooksSync( 7035):  }
E/BooksSync( 7035): }
E/BooksSync( 7035): 
E/BooksSync( 7035): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7035): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7035): 	... 8 more
I/BooksSync( 7035): Finished books sync
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1077420, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1097742237444; DSPS: 36111652; Offset : -4309834051
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{487ee6e type 2 when 1108300 android} when 1108300
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1117743844832; DSPS: 36767064; Offset : -4309813525
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1137745396698; DSPS: 37422475; Offset : -4309818108
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1157746918879; DSPS: 38077885; Offset : -4309821832
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1177748678142; DSPS: 38733303; Offset : -4309832588
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{2f9a390f type 2 when 1193988 android} when 1193988
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1197750894750; DSPS: 39388735; Offset : -4309813298
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1217752469742; DSPS: 40044147; Offset : -4309825143
,I/UsageStatsService( 1035): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1237754141192; DSPS: 40699562; Offset : -4309832107
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1257755716184; DSPS: 41354973; Offset : -4309813589
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1277757234615; DSPS: 42010383; Offset : -4309820933
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1297758307107; DSPS: 42665778; Offset : -4309816921
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1317759873089; DSPS: 43321189; Offset : -4309807023
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1337762093967; DSPS: 43976622; Offset : -4309813954
,I/[SystemUI]LGPowerUI( 1475): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1475): On Skip Timer : true
D/LEDHandler( 1978): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1978): Battery Level Remaining: 100%
D/LEDHandler( 1978): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1475): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1475): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1475): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1035): battery changed pluggedType: 2
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3830): Disconnected process message: 10, size: 0
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1357763949792; DSPS: 44632043; Offset : -4309819727
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1377766058431; DSPS: 45287472; Offset : -4309816671
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1397767297590; DSPS: 45942873; Offset : -4309828889
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1417768798831; DSPS: 46598282; Offset : -4309822879
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
,I/[SystemUI]DateView( 1475): called onTimeUpdated()
,I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1437770676377; DSPS: 47253703; Offset : -4309806932
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1457772538088; DSPS: 47909125; Offset : -4309837362
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1477774083913; DSPS: 48564535; Offset : -4309817338
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1497775733125; DSPS: 49219949; Offset : -4309816154
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1517777216450; DSPS: 49875358; Offset : -4309828164
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1537778737223; DSPS: 50530768; Offset : -4309833218
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,I/DigitalAppWidgetProvider( 7782): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7782): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2783d106
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1557780923258; DSPS: 51186199; Offset : -4309814036
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1577782690646; DSPS: 51841617; Offset : -4309816640
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1597784207670; DSPS: 52497027; Offset : -4309825443
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1617785761932; DSPS: 53152438; Offset : -4309827631
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1637787511821; DSPS: 53807855; Offset : -4309817191
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1657789211709; DSPS: 54463271; Offset : -4309826287
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1677791725347; DSPS: 55118713; Offset : -4309815194
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1697793537111; DSPS: 55774133; Offset : -4309834355
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1717795027832; DSPS: 56429541; Offset : -4309808634
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1737796821418; DSPS: 57084960; Offset : -4309815533
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1757798548077; DSPS: 57740377; Offset : -4309828350
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1777800714320; DSPS: 58395808; Offset : -4309828725
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1797802362020; DSPS: 59051222; Offset : -4309829104
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1817803856180; DSPS: 59706631; Offset : -4309830202
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1837805397317; DSPS: 60362041; Offset : -4309815047
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,W/bt-smp  ( 3830): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3830): Plain text(LSB ~ MSB) = 82 99 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3830): Encrypted text(LSB ~ MSB) = e4 23 bc 3b f6 9b 99 6a 33 f1 01 91 81 12 14 52 
,W/bt-btm  ( 3830): Stopping oneshot timer
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{19ee83a5 type 2 when 1842592 com.android.bluetooth} when 1842592
I/ProcessStatsService( 1035): Prepared write state in 27ms
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,I/ProcessStatsService( 1035): Prepared write state in 11ms
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,I/ProcessStatsService( 1035): Pruning old procstats: /data/system/procstats/state-2016-01-14-13-22-02.bin
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1857807205748; DSPS: 61017460; Offset : -4309807155
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{2d48837a type 0 when 1452861440340 com.google.android.gms} when 1452861440340
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{a4b572b type 2 when 1193232 com.google.android.gms} when 1193232
D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/LocationManagerService( 1035): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2334): Aggregate from 1452859640259 (log), 1452859640259 (data)
,D/GCM     ( 2141): Message class com.google.f.a.a.i
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1877808858500; DSPS: 61672875; Offset : -4309832816
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1897810442712; DSPS: 62328287; Offset : -4309835648
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
,I/[SystemUI]Clock( 1475): called onTimeUpdated()
I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1917812334423; DSPS: 62983709; Offset : -4309835819
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1937814158634; DSPS: 63639128; Offset : -4309812041
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1957816070709; DSPS: 64294551; Offset : -4309822886
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1977817639139; DSPS: 64949962; Offset : -4309810774
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1997819148038; DSPS: 65605372; Offset : -4309827780
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2017821263760; DSPS: 66260801; Offset : -4309817772
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2037822828440; DSPS: 66916212; Offset : -4309809411
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2057824591088; DSPS: 67571630; Offset : -4309816859
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2077826441653; DSPS: 68227051; Offset : -4309827866
,I/[SystemUI]TimeTickManager( 1475): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1475): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1475): called onTimeUpdated()
I/[SystemUI]Clock( 1475): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
I/[SystemUI]DateView( 1475): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1475): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2097828494301; DSPS: 68882478; Offset : -4309819870
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=1067099929, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{d4ba3f6 type 2 when 2105086 android} when 2105086
I/ActivityManager( 1035): Killing 7495:com.android.chrome/u0a57 (adj 15): empty for 1809s
I/ActivityManager( 1035): Killing 6650:com.wsandroid.suite.lge/1000 (adj 15): empty for 1809s
,I/ActivityManager( 1035): Killing 7472:com.lge.formmanager/u0a26 (adj 15): empty for 1809s
,I/ActivityManager( 1035): Killing 6758:com.lge.email/u0a23 (adj 15): empty for 1809s
,I/ActivityManager( 1035): Killing 7426:com.lge.appbox.client/u0a11 (adj 15): empty for 1809s
,I/ActivityManager( 1035): Killing 7257:com.android.settings/1000 (adj 15): empty for 1812s
,I/ActivityManager( 1035): Killing 7295:com.lge.sync/1000 (adj 15): empty for 1812s
,W/libprocessgroup( 1035): failed to open /acct/uid_10057/pid_7495/cgroup.procs: No such file or directory
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_7257/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_7295/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10026/pid_7472/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_6758/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_7426/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2640): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=1067099929 [*alarm*], flags=0x0
,TIME-OUT KILL (timeout was 1800000ms),I/BooksSync( 7035): Starting books sync
D/BooksSync( 7035): started syncMyEbooks
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3741191290097857623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 8067): 
D/AndroidRuntime( 8067): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8067): CheckJNI is OFF
I/art     ( 1035): Explicit concurrent mark sweep GC freed 44498(2MB) AllocSpace objects, 18(1164KB) LOS objects, 33% free, 44MB/66MB, paused 3.556ms total 297.536ms
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
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
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 8067): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1035): Killing 7168:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3741191290097857623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
W/PackageSettings( 1035): Skipping PackageSetting{3b6d11b5 com.example.hello/10319} due to missing metadata
D/WifiService( 1035): Client connection lost with reason: 4
I/WindowState( 1035): WIN DEATH: Window{f0d2b41 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1035): Window went away: Window{f0d2b41 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2ff93e12 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  330): DFP En is all cleared set to be enabled
W/ActivityManager( 1035): Spurious death for ProcessRecord{f8f1a8a 7168:com.test.thalitest/u0a311}, curProc for 7168: null
I/[LGHome]EVENT( 2094): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2094): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2094): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2094): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1931): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3758): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2094): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2094): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2094): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2094): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1931): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3758): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2094): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3758): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2094): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2094): , create_time: 1430558575574
I/GBoardWebViewUtils( 2094): , expire_time: 0
I/GBoardWebViewUtils( 2094): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2094): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2094): , display: false
I/GBoardWebViewUtils( 2094): , animation: false }
I/GBoardWebViewUtils( 2094): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2094): , create_time: 1430558575600
I/GBoardWebViewUtils( 2094): , expire_time: 0
I/GBoardWebViewUtils( 2094): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2094): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2094): , display: false
I/GBoardWebViewUtils( 2094): , animation: false }
I/GBoardWebViewUtils( 2094): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2094): , create_time: 1452774039338
I/GBoardWebViewUtils( 2094): , expire_time: 0
I/GBoardWebViewUtils( 2094): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2094): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2094): , display: false
I/GBoardWebViewUtils( 2094): , animation: false }
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1475): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@dee8014,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1475): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1475):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1475): , Keyguard show=false, IME shown=false, Panel expanded=false
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{246c6e2d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{2f8acf62 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/WallpaperManager( 2094): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]GBoardWebView( 2094): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2ff93e12 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1035): Duplicate finish request for ActivityRecord{2ff93e12 u0 com.test.thalitest/.MainActivity t4 f}
D/KeyguardModel( 1475): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3758): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/art     ( 4616): Explicit concurrent mark sweep GC freed 16170(919KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 554us total 56.109ms
D/LIA_Service_RemotePackageHandler( 2050): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
W/System.err( 4572): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4572): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4572): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4572): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4572): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4572): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4572): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4572): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4572): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4572): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4572): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4572): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
D/administrator( 1035): Handling package changes for user 0
D/WeatherAncestor( 7559): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:54:13
D/Weather.Utils( 7559): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7559): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7559): 2 : This is isUpdating : false
D/Weather.Utils( 7559): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7559): 2 : All the weather widget is gone.
D/WeatherAncestor( 7559): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:54:13
I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8127 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1475): onReceive = android.intent.action.PACKAGE_REMOVED
D/SplitUIManager( 1888): split_name #11 / not available #0
D/SplitUIService( 1888): removed split : 
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/ActivityManager( 1035): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/SplitUIManager( 1888): split_name #11 / not available #0
I/SplitUIService( 1888): split app #11
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1475): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1475): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ActivityManager( 1035): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]Launcher.Model( 2094): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 8144): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2094): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2094): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/LockScreenSettings( 8127): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]Launcher.Model( 2094): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2094): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2094): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{39990a44 u0 com.lge.launcher2/.Launcher t3} time:2109120
I/NotificationService( 1035): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/PluginManager( 8144): init()
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1035): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1035): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2094): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/[Concierge]WidgetView( 2094): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2640): onStartCommand(). Type : 8
D/[Concierge]Service( 2640): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2640): Update widget ID : 11
D/[Concierge]WidgetView( 2094): change position of spinner
D/KeyguardModel( 1475): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1475): createShortcutInfo...
I/[Concierge]WidgetView( 2094): initWebView(). Time : 1452862454162
D/[Concierge]Service( 2640): onStartCommand(). Type : 0
D/KeyguardModel( 1475): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1475): createShortcutInfo...
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1475): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1475): createShortcutInfo...
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1475): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1475): createShortcutInfo...
I/[Concierge]WebView( 2094): Return exist ConciergeWebView. Reuse : 374395627
D/[Concierge]WidgetView( 2094): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2094): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 1475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1475): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1475): createShortcutInfo...
I/[LgeWidgetLib]ExtViewHost( 2094): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@58d3413
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2094): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1475): handleShortcutListChanged...
D/KeyguardModel( 1475): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1475): createShortcutInfo...
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2094): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2094): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/KeyguardModel( 1475): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1475): createShortcutInfo...
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/[Concierge]WidgetView( 2094): Widget kill message received. Destory myself. My : 1452860373847, New one : 1452862454162
D/[Concierge]WidgetView( 2094): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2094): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1475): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1475): createShortcutInfo...
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1475): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1475): createShortcutInfo...
W/ResourceType( 1475): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1475): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1475): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1475): createShortcutInfo...
D/KeyguardModel( 1475): handleShortcutListChanged...
I/[LgeWidgetLib]LgeAppWidgetHostView( 2094): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2094): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2094): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2094): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1035): Explicit concurrent mark sweep GC freed 20546(1418KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.582ms total 262.138ms
I/ThermalEngine(  324): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3133): Thermal-Lib-Client: Client request sent
I/Timeline( 2094): Timeline: Activity_idle id: android.os.BinderProxy@2b47da76 time:2109262
W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2094): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AndroidRuntime( 8067): Shutting down VM
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 2094): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7035): Authentication error
E/BooksAccountManager( 7035): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7035): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7035): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7035): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7035): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14e95c25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GBoardtInterface( 2094): onReloaded()
I/GBoardWebViewClient( 2094): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3758): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3758): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1931): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3758): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3758): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1931): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3758): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3758): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3758): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3758): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3758): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2094): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2094): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2094): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2094): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2094): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2094): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ExternalStrings( 8144): load override strings
W/ExternalStrings( 8144): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 8144): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 8144): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 8144): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 8144): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 8144): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 8144): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 8144): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 8144): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 8144): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 8144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 8144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 8144): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 8144): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 8144): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 8144): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 8144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 8144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 8144): onCreate
W/ApiaryClient( 7035): Error response from books API: {
W/ApiaryClient( 7035):  "error": {
W/ApiaryClient( 7035):   "errors": [
W/ApiaryClient( 7035):    {
W/ApiaryClient( 7035):     "domain": "global",
W/ApiaryClient( 7035):     "reason": "required",
W/ApiaryClient( 7035):     "message": "Login Required",
W/ApiaryClient( 7035):     "locationType": "header",
W/ApiaryClient( 7035):     "location": "Authorization"
W/ApiaryClient( 7035):    }
W/ApiaryClient( 7035):   ],
W/ApiaryClient( 7035):   "code": 401,
W/ApiaryClient( 7035):   "message": "Login Required"
W/ApiaryClient( 7035):  }
W/ApiaryClient( 7035): }
W/ApiaryClient( 7035): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7035): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3741191290097857623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7035): Headers:
W/ApiaryClient( 7035): accept-encoding: [gzip]
W/ApiaryClient( 7035): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7035): gdata-version: 2
V/Signer  ( 8144): override build config not found
D/Signer  ( 8144): value of property debug is false
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 8144): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 8144): Create singleton instance
D/LGMDMWrapper( 8144): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 8144): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 8144): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8174 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 7533:com.lge.drmservice/u0a62 (adj 15): empty for 1813s
W/ActivityThread( 8144): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1035): failed to open /acct/uid_10062/pid_7533/cgroup.procs: No such file or directory
I/GBoardtInterface( 2094): exportHTML()
I/GBoardtInterface( 2094): exportHTML()
I/GBoardtInterface( 2094): exportHTML()

```
