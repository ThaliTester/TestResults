#### Test 55431344148e3f8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 257472615249; DSPS: 8577788; Offset : -4315811741
,D/AndroidRuntime( 7128): 
D/AndroidRuntime( 7128): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7128): CheckJNI is OFF
D/AndroidRuntime( 7128): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1966): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1d336f06 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1d336f06 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  336): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7148 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7128): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1880): Display #0 changed.
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{38f9e318 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{22273171 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7148): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7148): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7148): Loading: webviewchromium
,I/LibraryLoader( 7148): Time to load native libraries: 4 ms (timestamps 5015-5019)
I/LibraryLoader( 7148): Expected native library version number "",actual native library version number ""
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 26676(1174KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.901ms total 94.240ms
,V/WebViewChromiumFactoryProvider( 7148): Binding Chromium to main looper Looper (main, tid 1) {1cd618c8}
I/LibraryLoader( 7148): Expected native library version number "",actual native library version number ""
I/chromium( 7148): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7148): Initializing chromium process, renderers=0
W/art     ( 7148): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7148): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7148): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7148): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb14fd820, uid 10311
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f092360:true
I/Adreno-EGL( 7148): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7148): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7148): Build Date: 12/12/14 금
I/Adreno-EGL( 7148): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7148): Remote Branch: 
I/Adreno-EGL( 7148): Local Patches: 
I/Adreno-EGL( 7148): Reconstruct Branch: 
W/chromium( 7148): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7148): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7148): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7148): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{3f5e49c7 u0 com.test.thalitest/.MainActivity t4}
D/SystemWebViewEngine( 7148): CordovaWebView is running on device made by: LGE
W/art     ( 7148): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7148): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7148): Render dirty regions requested: true
I/OpenGLRenderer( 7148): Initialized EGL, version 1.4
D/OpenGLRenderer( 7148): Enabling debug mode 0
D/Atlas   ( 7148): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{2d6b9c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7148): LgDataFeature() Constructor: none
D/LgDataFeature( 7148): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d1afa62,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +724ms (total +793ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{3f5e49c7 u0 com.test.thalitest/.MainActivity t4} time:275562
I/Timeline( 7148): Timeline: Activity_idle id: android.os.BinderProxy@22a543f8 time:275571
D/JsMessageQueue( 7148): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7148): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7148): 
I/chromium( 7148): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7148): 
D/jxcore_app_log( 7148): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
D/JX-Cordova( 7148): jxcore cordova android initializing
E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
,I/GBMv2   (  336): DFP Enabled. Ignore VFP set
W/jxcore-log( 7148): Initializing JXcore engine
W/jxcore-log( 7148): JXcore engine is ready
,W/jxcore-log( 7148): Starting JXcore engine
W/.test.thalitest( 7148): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6144]" dev="sockfs" ino=6144 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7148): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7148): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7596]" dev="sockfs" ino=7596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7148): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7148): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34097]" dev="sockfs" ino=34097 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7148): Platform android
W/jxcore-log( 7148): 
W/jxcore-log( 7148): Process ARCH arm
W/jxcore-log( 7148): 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 277473971148; DSPS: 9233193; Offset : -4315828690
I/jxcore-log( 7148): JXcore Cordova bridge is ready!
I/jxcore-log( 7148): 
W/jxcore-log( 7148): JXcore engine is started
,I/jxcore-log( 7148): Toggling radios to true
I/jxcore-log( 7148): 
,D/BluetoothAdapter( 7148): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=7148, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=7148, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1036): disconnect pid=7148, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1036): [279,059,052 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1036): reconnect pid=7148, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7148): Radios toggled
I/jxcore-log( 7148): 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7148): Received device characteristics:
I/jxcore-log( 7148): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7148): Bluetooth name: G3-1
I/jxcore-log( 7148): Device name: LGE-LG-D855
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Perf Test app loaded loaded
I/jxcore-log( 7148): 
I/jxcore-log( 7148): check test folder
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): found test : ./testFindPeers.js
I/jxcore-log( 7148): 
I/wpa_supplicant( 2728): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/jxcore-log( 7148): found test : ./testSendData.js
I/jxcore-log( 7148): 
D/Tethering( 1036): InitialState.processMessage what=4
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1036): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2133): Read error: ssl=0xaa6dce00: I/O error during system call, Connection timed out
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 2133): SSL shutdown failed: ssl=0xaa6dce00: I/O error during system call, Broken pipe
,D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
,D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1036): [279,224,708 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2728): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1036): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiNative-wlan0( 1036): RECONNECT: returned true
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkM,anagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279233
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279233
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1880): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,D/CommandListener(  309): Clearing all IP addresses on wlan0
D/WifiHS20( 1036): hidePasspointNotification off =false
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279240  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279240  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279263  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279277  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7226): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7226): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7226): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7226): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7226): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/Choreographer( 7148): Skipped 90 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7148): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7148): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7226): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7226): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7226): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7226): [AUTORUN] getUsbConnected() : connected=true
D/DhcpStateMachine( 1036): StoppedState
,D/DhcpStateMachine( 1036): StoppedState{ when=-185ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7226): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7226): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7248 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6548:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6548/cgroup.procs: No such file or directory
,I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7226): LgDataFeature() Constructor: none
,D/LgDataFeature( 7226): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
,I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7275 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1036): Killing 6697:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6697/cgroup.procs: No such file or directory
,W/ResourcesManager( 7275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7275): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7275): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7275): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7275): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7275): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7275): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7275): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7275): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7275): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7275): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7275): LgDataFeature() Constructor: none
D/LgDataFeature( 7275): LgDataFeature() Constructor Done, null
,V/SoundPool( 7275): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7275): load: fd=31, offset=10857164, length=17813, priority=1
V/SoundPool( 7275): create sampleID=1, fd=30, offset=17813 length=10857164
V/SoundPool( 7275): doLoad: loading sample sampleID=1
I/QRemote ( 7275): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7275): Start decode
V/MediaPlayer[Native]( 7275): decode(30, 10857164, 17813)
,V/MediaPlayerService(  313): decode(24, 10857164, 17813)
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
V/AudioCache(  313): notify(0xb1432bc0, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  313): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6834): QS Service created
D/QRemote ( 7275): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7275): Create singleton instance
I/UEI.SmartControl( 6834): Service initServices...
D/UEI.SmartControl( 6834): QS start get config
,V/LGParserOSAL(  313): supported mime: application/ogg
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
D/OMXCodec(  313): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
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
,I/AwesomePlayer(  313): Could not offload audio decode, try pcm offload
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcc40 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1661330 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1661380 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb16613d0 on output port
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  313): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  313): finishAsyncPrepare_l() 
V/AudioCache(  313): notify(0xb1432bc0, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb1432bc0, 1, 0, 0)
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  313): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797504
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976256816
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976256896
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313,): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976256976
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1661380 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1661330 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb1432bc0, 6, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab602000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab603000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab604000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab605000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab606000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab607000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab608000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab609000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60a000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60b000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60c000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60d000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60e000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab60f000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab610000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab611000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab612000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab613000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab614000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab615000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab616000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab617000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab618000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab619000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61a000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61b000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61c000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61d000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61e000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab61f000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab620000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab621000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab622000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab623000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab624000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab625000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab626000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab627000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab628000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab629000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62a000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62b000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62c000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62d000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62e000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab62f000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab630000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab631000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab632000, 0xb169c000, 4096)
V/AudioCache(  313): write(0xb169c000, 4096)
V/AudioCache(  313): memcpy(0xab633000, 0xb169c000, 4096)
,V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb169c000, 280)
V/AudioCache(  313): memcpy(0xab634000, 0xb169c000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb1432bc0, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): wait - success
V/AudioCache(  313): notify(0xb1432bc0, 7, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  313): cancelPlayerEvents
D/AudioPlayer(  313): Pause Playback at 1068125
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1432bc0, 8, 0, 0)
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcc40 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcec0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1661330 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1661380 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
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
V/SoundPool( 7275): close(30)
V/SoundPool( 7275): pointer = 0xa0016000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7275): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting,
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6811
I/UEI.SmartControl( 6834): Supports setup maps: true
,D/UEI.SmartControl( 6834): QS start statue = true Error code = 0
I/UEI.SmartControl( 6834): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6834): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6834): ### init IR Blaster...
D/serial_port( 6834): Configuring serial port
E/UEI.SmartControl( 6834): UEIBLaster setting for 616
I/UEI.SmartControl( 6834): Setting serial record hearder size = 2
I/UEI.SmartControl( 6834): configuring settings for MAXQ616
I/UEI.SmartControl( 6834): Get version...
D/UEI.SmartControl( 6834): serial port data available: 21
,D/UEI.SmartControl( 6834): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6834): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6834): QS saving settings...
,D/UEI.SmartControl( 6834): IR Blaster version: 25672567
D/UEI.SmartControl( 6834): serial port data available: 4
,I/UEI.SmartControl( 6834): Device manager: loading config....
D/UEI.SmartControl( 6834): ----------- loading internal config...
,W/ContextImpl( 6834): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6834): Services init done
D/UEI.SmartControl( 6834): QS Service init finished
E/UEI.SmartControl( 6834): Loading SETTINGS...
,D/UEI.SmartControl( 6834): QS Service version name: 2.1.91
D/UEI.SmartControl( 6834): QS Service version code: 201091
D/UEI.SmartControl( 6834): Service requested: Control
I/QRemote ( 7275): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6834): Internal service binding...
I/UEI.SmartControl( 6834): ------ IControl API: 11
D/UEI.SmartControl( 6834): File observer start...
E/UEI.SmartControl( 6834): IR Port is disabled: false
D/UEI.SmartControl( 6834): Starting file observer...
D/UEI.SmartControl( 6834): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6834): Registering callback...
I/UEI.SmartControl( 6834): ------ IControl API: 19
,I/UEI.SmartControl( 6834): Registering Services Ready callback...
I/UEI.SmartControl( 6834): Notify AllClients services are ready: 0
I/QRemote ( 7275): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7275): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/UEI.SmartControl( 6834): -----service ready thread exits
D/QRemote ( 7275): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7275): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7275): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6834): ------ IControl API: 8
D/QRemote ( 7275): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7275): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7275): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7275): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 7275): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7275): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7275): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 7275): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7275): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452246691067]
D/QRemote ( 7275): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6110:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7275): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6110/cgroup.procs: No such file or directory
,V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2728): Trying to associate with SSID 'NG700'
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
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281313  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281349  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2728): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281422  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2728): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2728): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281423  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281443
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281446
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281447
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281447
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281448
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281449  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281451  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281452  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281457  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281458
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281459
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7226): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7226): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7226): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
D/UsbSettingsControl( 7226): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7226): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7226): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7226): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1036): Got NetworkAgent Messenger
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1036): NetworkAgent connected
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281517  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281517  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281518  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1036):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1036):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281523  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281524  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281525  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b3ed727 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b3ed727 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1036): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1458): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/Netd    (  309): netlink response contains error (File exists)
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1880): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168,.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
I/StatusBar.NetworkController( 1458): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524290
,W/dsqn    ( 7343): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7343): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 7343): DSQN ssw
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 09:51:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452246691963], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452246691937]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
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
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1880): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1880):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7275): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7275): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7275): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7226): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7275): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7275): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7275): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7349): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7349): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7349): version 5.5.6 starting
,E/dhcpcd  ( 7349): get_duid: m
D/dhcpcd  ( 7349): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7349): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7349): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7349): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7349): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7349): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7349): wlan0: sending REQUEST (xid 0xc23105a9), next in 4.19 seconds
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7367 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  340): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 37.743ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 19.792ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 18.604ms
,I/AppUp4:AppBoxCP( 7367): onCreate
W/AppUp4:DB( 7367):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7367):  setFingerPrint start
I/AppUp4:DB( 7367):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7367):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7367):  SDK version = 21
I/AppUp4:DB( 7367):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7367): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7367): onReceive
D/LgDataFeature( 7367): LgDataFeature() Constructor: none
D/LgDataFeature( 7367): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7367): Context : android.app.ReceiverRestrictedContext@31249086
D/AppUp4:CustFacade( 7367): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7367): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7367): begin check event
I/AppUp4:CustModeStarterReceiver( 7367): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7367): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7367): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7367): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7367): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6133:com.android.contacts/u0a19 (adj 15): empty #17
,D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6133/cgroup.procs: No such file or directory
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3436): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3436): DownloadService onCreate
,D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3436): in removeSpuriousFiles
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3436): DownloadService onStartCommand
V/DownloadManager( 3436): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@21521e58 on behalf of 3436
,D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@545ebb1 on behalf of 3436
V/DownloadManager( 3436): processing inserted download 1
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
V/DownloadManager( 3436): processing inserted download 4
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3436): processing inserted download 7
V/DownloadManager( 3436): processing inserted download 8
I/DownloadManager( 3436): in trimDatabase
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3436): processing inserted download 9
V/DownloadManager( 3436): processing inserted download 10
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@87b7896 on behalf of 3436
V/DownloadManager( 3436): processing inserted download 16
V/DownloadManager( 3436): processing inserted download 17
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3436): processing inserted download 18
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3436): processing inserted download 21
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/eas_req ( 6722): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3436): DownloadService onDestroy
I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7411 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6722): JNI_OnLoad()
,I/HubEmail( 6722): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6722): registerNatives()
I/HubEmail( 6722): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6722): registerNativeMethods()
I/HubEmail( 6722): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6722): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = false
,I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7435 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 7349): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7349): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7349): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7349): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7349): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7349): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 7349): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7349): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7349): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7469 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6749:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6749/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7495 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6772:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
V/FormManager( 7411): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7411): Alarm would be updated, because LastCheckTime has been updated.
E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6772/cgroup.procs: No such file or directory
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524295
,I/ActivityManager( 1036): Killing 6808:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     ( 7495): Almond Protected OAT
W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6808/cgroup.procs: No such file or directory
,D/WeatherApplication( 7495): removeAccount
D/WeatherApplication( 7495): Account.length = 0
E/WeatherApplication( 7495): OPERATOR:OPEN
D/WeatherAncestor( 7495): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:33
,D/Weather.Utils( 7495): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7495): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7495): 2 : This is isUpdating : false
D/WeatherAncestor( 7495): connectivity changed - connection : true
D/WeatherService( 7495): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7495): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7495): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7495): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7495): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7495): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:33
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7514 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6886:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6886/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7514): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7514): Loading: webviewchromium
,I/LibraryLoader( 7514): Time to load native libraries: 6 ms (timestamps 4061-4067)
I/LibraryLoader( 7514): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7514): Binding Chromium to main looper Looper (main, tid 1) {8eaa909}
I/LibraryLoader( 7514): Expected native library version number "",actual native library version number ""
,I/chromium( 7514): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7514): Initializing chromium process, renderers=0
W/art     ( 7514): Attempt to remove local handle scope entry from IRT, ignoring
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7148): BLE is supported
I/jxcore-log( 7148): 
W/chromium( 7514): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7514): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7514): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb14272a0, uid 10093
,W/AudioManagerAndroid( 7514): Requires BLUETOOTH permission
I/Adreno-EGL( 7514): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7514): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7514): Build Date: 12/12/14 금
I/Adreno-EGL( 7514): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7514): Remote Branch: 
I/Adreno-EGL( 7514): Local Patches: 
I/Adreno-EGL( 7514): Reconstruct Branch: 
,I/NSApplication( 7514): Starting up...
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/ActivityManager( 1036): Killing 6910:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6910/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7367): onReceive
,D/AppUp4:CustFacade( 7367): Context : android.app.ReceiverRestrictedContext@31249086
D/AppUp4:CustFacade( 7367): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7367): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7367): begin check event
I/AppUp4:CustModeStarterReceiver( 7367): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3436): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3436): DownloadService onCreate
,D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3436): in removeSpuriousFiles
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@ff6c804 on behalf of 3436
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3436): in trimDatabase
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@341c91ed on behalf of 3436
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3436): DownloadService onStartCommand
V/DownloadManager( 3436): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@3b1a6070 on behalf of 3436
V/DownloadManager( 3436): processing inserted download 1
,V/DownloadManager( 3436): processing inserted download 4
I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3436): processing inserted download 7
V/DownloadManager( 3436): processing inserted download 8
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = false
V/DownloadManager( 3436): processing inserted download 9
V/DownloadManager( 3436): processing inserted download 10
V/DownloadManager( 3436): processing inserted download 16
V/DownloadManager( 3436): processing inserted download 17
,V/DownloadManager( 3436): processing inserted download 18
V/DownloadManager( 3436): processing inserted download 21
D/WeatherAncestor( 7495): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:34
D/Weather.Utils( 7495): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7495): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7495): 2 : This is isUpdating : false
D/WeatherAncestor( 7495): connectivity changed - connection : true
D/WeatherService( 7495): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b97f974
D/ForecastDataCache( 7495): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7495): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7495): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7495): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7495): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:34
V/DownloadManager( 3436): DownloadService onDestroy
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/Kids    ( 2326): [AccountUtils] Account not ready
W/Kids    ( 2326): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2326): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2326): 	at java.lang.Thread.run(Thread.java:818)
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
,V/FormManager( 7411): There are no updated forms. The schedule will be deleted.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/FormManager( 7411): Alarm would be updated, because LastCheckTime has been updated.
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=true
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2326): [AccountUtils] Account not ready
W/Kids    ( 2326): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2326): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2326): 	at java.lang.Thread.run(Thread.java:818)
,D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7367): [onReceive] request level :IDLE....
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/AppUp4:CustModeStarterReceiver( 7367): onReceive
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/AppUp4:CustFacade( 7367): Context : android.app.ReceiverRestrictedContext@31249086
D/AppUp4:CustFacade( 7367): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7367): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7367): begin check event
I/AppUp4:CustModeStarterReceiver( 7367): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3436): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3436): DownloadService onCreate
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
D/LGDMClient( 4312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/LGDMClient( 4312): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3436): in removeSpuriousFiles
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@3b9d139c on behalf of 3436
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
V/DownloadManager( 3436): DownloadService onStartCommand
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
,I/DownloadManager( 3436): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3436): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3436): in trimDatabase
V/DownloadManager( 3436): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 6722): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7411): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7411): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1036): Explicit concurrent mark sweep GC freed 83924(3MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.604ms total 98.211ms
,V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@48311a5 on behalf of 3436
V/DownloadManager( 3436): created cursor android.database.sqlite.SQLiteCursor@25ccf97a on behalf of 3436
I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = true
D/PhoneState( 3371): setPdpRejectCasuse : false
E/LGDMClient( 4312): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3436): processing inserted download 1
D/LGDMClient( 4312): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4312): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3436): processing inserted download 4
,V/DownloadManager( 3436): processing inserted download 7
V/DownloadManager( 3436): processing inserted download 8
V/DownloadManager( 3436): processing inserted download 9
V/DownloadManager( 3436): processing inserted download 10
V/DownloadManager( 3436): processing inserted download 16
V/DownloadManager( 3436): processing inserted download 17
V/DownloadManager( 3436): processing inserted download 18
V/DownloadManager( 3436): processing inserted download 21
D/WeatherAncestor( 7495): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:35
D/Weather.Utils( 7495): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7495): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7495): 2 : This is isUpdating : false
D/WeatherAncestor( 7495): connectivity changed - connection : true
D/WeatherService( 7495): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b97f974
,D/ForecastDataCache( 7495): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7495): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7495): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7495): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7495): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:51:35
V/DownloadManager( 3436): DownloadService onDestroy
D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2326): [AccountUtils] Account not ready
W/Kids    ( 2326): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2326): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2326): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2326): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2326): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2326): 	at java.lang.Thread.run(Thread.java:818)
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
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=908086202, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{28f572d3 type 2 when 284989 com.google.android.gms} when 284989
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=908086202 [*alarm*], flags=0x0
,D/GCM     ( 2133): Connected
,D/GCM     ( 2133): Message class com.google.f.a.a.p
I/jxcore-log( 7148): Connected to the server!
I/jxcore-log( 7148): 
,I/chromium( 7148): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/UEI.SmartControl( 6834): Internal timer expired: 3
D/UEI.SmartControl( 6834): unbind internal service
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
D/serial_port( 6834): close(fd = 24)
I/UEI.SmartControl( 6834): Serial port is closed.
,D/libc-netbsd(  309): res_queryN name = www.google.com succeed
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7514): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2d9a692f type 2 when 297254 android} when 297254
,V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6811
,I/BooksSync( 6997): Starting books sync
,D/BooksSync( 6997): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 297478996765; DSPS: 9888718; Offset : -4315838370
,W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3483513233140361493&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3483513233140361493&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3483513233140361493&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
E/BooksSync( 6997): Soft error: 
E/BooksSync( 6997): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3483513233140361493&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6997): Headers:
E/BooksSync( 6997): accept-encoding: [gzip]
E/BooksSync( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6997): gdata-version: 2
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6997): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6997): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6997): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6997): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6997): {
E/BooksSync( 6997):  "error": {
E/BooksSync( 6997):   "errors": [
E/BooksSync( 6997):    {
E/BooksSync( 6997):     "domain": "global",
E/BooksSync( 6997):     "reason": "required",
E/BooksSync( 6997):     "message": "Login Required",
E/BooksSync( 6997):     "locationType": "header",
E/BooksSync( 6997):     "location": "Authorization"
E/BooksSync( 6997):    }
E/BooksSync( 6997):   ],
E/BooksSync( 6997):   "code": 401,
E/BooksSync( 6997):   "message": "Login Required"
E/BooksSync( 6997):  }
E/BooksSync( 6997): }
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6997): 	... 8 more
,E/BooksSync( 6997): Sync error
E/BooksSync( 6997): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3483513233140361493&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6997): Headers:
E/BooksSync( 6997): accept-encoding: [gzip]
E/BooksSync( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6997): gdata-version: 2
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6997): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6997): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6997): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6997): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6997): {
E/BooksSync( 6997):  "error": {
E/BooksSync( 6997):   "errors": [
E/BooksSync( 6997):    {
E/BooksSync( 6997):     "domain": "global",
E/BooksSync( 6997):     "reason": "required",
E/BooksSync( 6997):     "message": "Login Required",
E/BooksSync( 6997):     "locationType": "header",
E/BooksSync( 6997):     "location": "Authorization"
E/BooksSync( 6997):    }
E/BooksSync( 6997):   ],
E/BooksSync( 6997):   "code": 401,
E/BooksSync( 6997):   "message": "Login Required"
E/BooksSync( 6997):  }
E/BooksSync( 6997): }
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6997): 	... 8 more
I/BooksSync( 6997): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297254, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 317481764102; DSPS: 10544168; Offset : -4315817849
,E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=908086202, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{14531721 type 2 when 327323 android} when 327323
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=908086202 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 337484151281; DSPS: 11199606; Offset : -4315810937
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 357486315648; DSPS: 11855037; Offset : -4315813266
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=908086202, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
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
,W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 6251): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6251): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6251): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6251): 	at android.os.Binder.execTransact(Binder.java:446)
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=908086202 [*alarm*], flags=0x0
,W/System  ( 6251): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 377488257255; DSPS: 12510461; Offset : -4315824706
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 397490647821; DSPS: 13165899; Offset : -4315814615
,I/jxcore-log( 7148): --- start :testFindPeers.js---
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): testFindPeers created [object Object]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): serverPort is 8876
I/jxcore-log( 7148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7148): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3818): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): start: OK
I/io.jxcore.node.ConnectionHelper( 7148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7148): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7148): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7148): start: OK
I/jxcore-log( 7148): StartBroadcasting started ok
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7148): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7148): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1036):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 33
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1036):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 33
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services,
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
,D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-21ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-21ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7148): 
D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-18ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-18ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-18ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-19ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-20ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-20ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-20ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036): InactiveState{ when=-23ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-23ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-23ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-26ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-26ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-26ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-28ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-28ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-28ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-28ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-29ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-29ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-18ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-18ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-18ms what=139283 arg2=10 target=com.android.int,ernal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7148): 
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7148): 
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000101000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7148): 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139310 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=8 target=com,.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000102000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7148): 
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000102000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7148): 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 417492949011; DSPS: 13821334; Offset : -4315802425
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=71 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 437495107597; DSPS: 14476765; Offset : -4315810483
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=73 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 3 120001030a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
,D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=77 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=78 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-18ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-18ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-18ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-20ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-20ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-20ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7148): 
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7148): 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=83 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=86 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=89 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=91 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 457497257537; DSPS: 15132196; Offset : -4315827317
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=93 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1,036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-18ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-18ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-18ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Pee,r 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=96 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7148): 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=102 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=103 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=104 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=105 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=107 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=110 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=111 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9,:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=114 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 477499455914; DSPS: 15787628; Offset : -4315826259
,I/wpa_supplicant( 2728): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac]
D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=117 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=119 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=120 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=122 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=124 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=126 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=127 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=128 dispatchEvent: P2P-SERV-DISC-REQ 2462 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7148): onPeerLost: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] removed
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] not available
I/jxcore-log( 7148): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":false}]
I/jxcore-log( 7148): 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 497501736845; DSPS: 16443062; Offset : -4315803602
,I/jxcore-log( 7148): timeout now
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): weAreDoneNow
I/jxcore-log( 7148): 
I/jxcore-log( 7148): done, now sending data to server
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=129 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pE,nabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=130 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=131 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=132 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=60 target=com.android.internal.uti,l.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000109000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=134 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 3 120001080a436f72646f7661703270c00c000c01
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=135 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 3 120001060a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=138 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 517503842879; DSPS: 17098492; Offset : -4315833667
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=139 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=140 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=141 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=142 dispatchEvent: P2P-SERV-DISC-REQ 2462 52:55:27:f0:fd:0b 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=143 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=144 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e ,92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=146 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=147 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 5500010a000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
W/bt-l2cap( 3818): l2c_link_hci_conn_req:current link_role= 1
,W/bt-btm  ( 3818): btm_acl_created hci_handle=1 link_role=1  transport=1
,W/bt-btm  ( 3818): btm_acl_created hci_handle=1 link_role=1  transport=1
,W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: 7c-f9-0e-34-8a-a0
,W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-34-8a-a0
,W/bt-btif ( 3818): info:x10
D/        ( 3818): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3818): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3818): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0040  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e6b5ce:true
,W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x0040
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
D/LGBluetoothFeatureConfig( 7226): isPrivacyLogsEnabled : true
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 1
I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3818): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3818): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3818): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3818): Entering PendingCommandState State
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7714 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3693fc:true
,I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothRemoteDevices( 3818): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3818): Failed to remove device: 7C:F9:0E:34:8A:A0
I/BluetoothBondStateMachine( 3818): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3818): StableState(): Entering Off State
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0041  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3818): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3818): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection initialized (thread ID: 826)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Entering thread (ID: 826)
E/ActivityThread( 7714): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7714): No ProfileInfo entries
I/LG Account v2.2( 7714): isEnabled: false
I/Feature ( 7714): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7714): [Lifetracker]Country: EU
I/Feature ( 7714): [Lifetracker]Operator: OPEN
I/Feature ( 7714): [Lifetracker]Ranking support: false
I/Feature ( 7714): [Lifetracker]Comfort support: false
I/Feature ( 7714): [Lifetracker]Accessory: true
I/Feature ( 7714): [Lifetracker]Health device: true
I/Feature ( 7714): [Lifetracker]Extra Pedometer: false
I/Feature ( 7714): [Lifetracker]Blood glucose device: false
I/Feature ( 7714): [Lifetracker]Device Number: 3
I/ActivityManager( 1036): Killing 6938:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesRead: Read 63 bytes successfully (thread ID: 826)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesWritten: 63 bytes successfully written (thread ID: 826)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): removeThreadFromList: Removing thread with ID 826
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Handshake thread disposed (thread ID: 826)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Exiting thread (ID: 826)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 S5-1]
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7148): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 7148): Entering thread (ID: 827)
E/io.jxcore.node.IncomingSocketThread( 7148): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 8876): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 7148): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 8876): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:52)
E/io.jxcore.node.IncomingSocketThread( 7148): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 7148): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 7148): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 8876): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 827
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 7148): closeBluetoothSocketAndStreams
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.IncomingSocketThread( 7148): Exiting thread (ID: 827)
,W/bt-rfcomm( 3818): rfc_port_closed,
W/bt-btif ( 3818): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
E/bt-btif ( 3818): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0041
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 17
,W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6938/cgroup.procs: No such file or directory
,W/bt-l2cap( 3818): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3818): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=2 link_role=0  transport=1
W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
W/bt-btif ( 3818): info:x10
,D/        ( 3818): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3818): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3818): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-btm  ( 3818): BTM_SwitchRole BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: 90e7c4f66977  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 2
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d3050 rs_disc_pending=1
W/bt-btif ( 3818): bta_dm_check_av:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,E/bt-btif ( 3818): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3818): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3818): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3818): Entering PendingCommandState State
I/jxcore-log( 7148): teardown
I/jxcore-log( 7148): 
I/jxcore-log( 7148): testFindPeers stopped
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2728): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1966): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7148): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setState: NOT_STARTED
I/jxcore-log( 7148): StopBroadcasting went ok
I/jxcore-log( 7148): 
I/jxcore-log( 7148): --- start :testSendData.js---
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 14
I/jxcore-log( 7148): 
I/jxcore-log( 7148): daya100000
I/jxcore-log( 7148): 
I/jxcore-log( 7148): check server
I/jxcore-log( 7148): 
I/jxcore-log( 7148): serverPort is 37082
I/jxcore-log( 7148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7148): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): start: OK
I/io.jxcore.node.ConnectionHelper( 7148): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7148): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7148): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=150 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7148): start: OK
I/jxcore-log( 7148): StartBroadcasting started ok
I/jxcore-log( 7148): 
I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
D/BluetoothRemoteDevices( 3818): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3818): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 3818): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3818): StableState(): Entering Off State
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0043  Result: 0  Status: 0  BDA: 90e7c4f66977  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0041,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0041,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/jxcore-log( 7148): [ { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 7148):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 7148):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 7148):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 7148):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 7148):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 7148):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 7148):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 7148):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 7148):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 7148):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 7148):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 7148):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 7148):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 } ]
I/jxcore-log( 7148): 
I/jxcore-log( 7148): startWithNextDevice
I/jxcore-log( 7148): 
I/jxcore-log( 7148): do fake peer & start
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:36.090Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:36.091Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:36.091Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 7148): 2016-01-08T09:55:36.099Z SendDataTCPServer.js: TCP/IP server is bound to port: 37082
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 829)
I/io.jxcore.node.ConnectionHelper( 7148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7148): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2728): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1966): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7148): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: RESTARTING
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/chromium( 7148): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7148): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3818): [BTUI] connectSocket FD=85 mFd=84
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3818): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3818): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection initialized (thread ID: 830)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Entering thread (ID: 830)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesRead: Read 70 bytes successfully (thread ID: 830)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Got valid identity from [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesWritten: 63 bytes successfully written (thread ID: 830)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): removeThreadFromList: Removing thread with ID 830
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Handshake thread disposed (thread ID: 830)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnected: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC One M8s]
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Exiting thread (ID: 830)
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC One M8s], created successfully
D/io.jxcore.node.ConnectionHelper( 7148): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7148): Entering thread (ID: 831)
,I/io.jxcore.node.IncomingSocketThread( 7148): Local host address: localhost/127.0.0.1, port: 37082
D/io.jxcore.node.IncomingSocketThread( 7148): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7148): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7148): Exiting thread (ID: 831)
I/jxcore-log( 7148): 2016-01-08T09:55:36.239Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7148): 
D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 832, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 833, name: Receiver)
,E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -1
,I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 1
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8125800:true
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: S5-1
I/jxcore-log( 7148): 2016-01-08T09:55:37.865Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:37.898Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:37.903Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:37.966Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:37.977Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:37.981Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:37.995Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:37.999Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.005Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.009Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.046Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.059Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.113Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.129Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.163Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.167Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.170Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.177Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.182Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.187Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.224Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 7148): 
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
,I/jxcore-log( 7148): 2016-01-08T09:55:38.281Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.287Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.298Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.302Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.334Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.339Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.342Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.345Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.353Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.358Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.404Z SendDataTCPServer.js: TCP/IP server has received 52470 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.409Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.413Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.423Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.429Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.438Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.444Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.447Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.451Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.456Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 7148): 
,W/bt-btm  ( 3818): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=4 link_role=0  transport=1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
I/jxcore-log( 7148): 2016-01-08T09:55:38.494Z SendDataTCPServer.js: TCP/IP server has received 66330 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.500Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.511Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.545Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.551Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.556Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.595Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.607Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.613Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.633Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.640Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.675Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.697Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.707Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.714Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.720Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.723Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.726Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.763Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.767Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.770Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:38.776Z SendDataTCPServer.js: TCP/IP server has received 99990 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:38.781Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7148): 
,W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3818): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3818): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3818): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d3218 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 2
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3818): BTM_SwitchRole BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3818): Requested New Role: 0
W/bt-btif ( 3818): invalid rfc slot id: 8
W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 833, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7148): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 831
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 833
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 832
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local input stream...
W/bt-btm  ( 3818): invalid rfc slot id: 8
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 832, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7148): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/jxcore-log( 7148): 2016-01-08T09:55:39.241Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7148): 
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7148): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 832, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 833, name: Receiver)
W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0044
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 21
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d3218 rs_disc_pending=1
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x01
W/bt-btm  ( 3818): BTM: RemBdAddr: 90e7c4f66977
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3818): check_cod: remote_cod = 0x5a020c
W/LGMDMUISystemServiceAdapter( 3818): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3818): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3818): Entering PendingCommandState State
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): Start timer timeout, starting now...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=152 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/BluetoothBondStateMachine( 3818): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothRemoteDevices( 3818): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3818): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3818): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3818): StableState(): Entering Off State
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
,W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=1
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x01
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0043,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0043,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-btm  ( 3818): BTM_SwitchRole BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-btm  ( 3818): BTM_SwitchRole BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3818): new conn_srvc id:26, app_id:1
W/bt-btif ( 3818): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3818): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3818): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onSocketConnected: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 829)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): onBytesWritten: 63 bytes successfully written (thread ID: 834)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Outgoing connection initialized (*handshake* thread ID: 834)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 829)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Entering thread (ID: 834)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): onBytesRead: Read 63 bytes successfully (thread ID: 834)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Handshake succeeded with [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onHandshakeSucceeded: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Exiting thread (ID: 834)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnected: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7148): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7148): Entering thread (ID: 835)
,D/io.jxcore.node.OutgoingSocketThread( 7148): Server socket local port: 37592
I/io.jxcore.node.OutgoingSocketThread( 7148): Now accepting connections...
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d3218 rs_disc_pending=1
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x01
W/bt-btm  ( 3818): BTM: RemBdAddr: 90e7c4f66977
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 7148): onListeningForIncomingConnections: Outgoing connection is using port 37592 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 7148): 2016-01-08T09:55:42.568Z SendDataConnector.js: CLIENT connected to 37592, error: null
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:42.569Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7148): 
I/io.jxcore.node.OutgoingSocketThread( 7148): Incoming data from address: /127.0.0.1, port: 37592
D/io.jxcore.node.OutgoingSocketThread( 7148): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7148): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7148): Exiting thread (ID: 835)
,I/jxcore-log( 7148): 2016-01-08T09:55:42.586Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7148): 
D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 837, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 836, name: Sender)
W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=1
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x01
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=153 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=154 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:e7:c4:e6:4c:f8 0 7 120001090a436f72646f7661703270c00c000c01
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0043
,I/jxcore-log( 7148): 2016-01-08T09:55:44.337Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7148): 
,D/btif_config_util( 3818): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63816
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=155 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 20
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7148): 2016-01-08T09:55:45.734Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7148): 
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001070a436f72646f7661703270c00c000c01
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 17
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=157 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7148): 2016-01-08T09:55:46.681Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,I/jxcore-log( 7148): 2016-01-08T09:55:47.659Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 537506042819; DSPS: 17753924; Offset : -4315831099
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c]
D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126,
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=161 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01
I/jxcore-log( 7148): 2016-01-08T09:55:48.584Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7148): 
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/jxcore-log( 7148): 2016-01-08T09:55:48.988Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7148): 
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
,D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b60376a0
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=162 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
I/jxcore-log( 7148): 2016-01-08T09:55:49.102Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7148): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -2
,I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: HTC One M8s
D/        ( 3818): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2436
,I/jxcore-log( 7148): 2016-01-08T09:55:50.074Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=164 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
I/jxcore-log( 7148): 2016-01-08T09:55:50.386Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7148): 
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=165 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
I/jxcore-log( 7148): 2016-01-08T09:55:50.694Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.695Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7148): 
I/jxcore-log( 7148): oneRoundDownNow
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.699Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.700Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7148): 
,D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 7148): close
D/io.jxcore.node.OutgoingSocketThread( 7148): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 837
D/io.jxcore.node.OutgoingSocketThread( 7148): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 836
D/io.jxcore.node.OutgoingSocketThread( 7148): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 836, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7148): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7148): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7148): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 837, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7148): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 836, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 837, name: Receiver)
I/jxcore-log( 7148): 2016-01-08T09:55:50.725Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 7148): 
I/jxcore-log( 7148): ---- round done--------
I/jxcore-log( 7148): 
I/jxcore-log( 7148): startWithNextDevice
I/jxcore-log( 7148): 
I/jxcore-log( 7148): do fake peer & start
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.727Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.727Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:50.728Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 7148): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 838)
W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3818): BTM_SwitchRole BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-rfcomm( 3818): rfc_port_closed
W/bt-btif ( 3818): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 120001070a436f72646f7661703270c00c000c01
W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=1
,W/bt-btif ( 3818): bta_dm_check_av:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0045
,W/bt-btm  ( 3818): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=6 link_role=0  transport=1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: f4-f1-e1-5c-3b-e2
,W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: f4-f1-e1-5c-3b-e2
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3818): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3818): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3818): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 2
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0046
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 11
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 838)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 838)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 838)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 7148): 2016-01-08T09:55:53.102Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:53.102Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:53.103Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 838)
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x00
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 20
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 20
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0047  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x00
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x0047
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x0048  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x0047,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x0047,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3818): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3818): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection initialized (thread ID: 840)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Entering thread (ID: 840)
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x00
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesRead: Read 63 bytes successfully (thread ID: 840)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Got valid identity from [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesWritten: 63 bytes successfully written (thread ID: 840)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): removeThreadFromList: Removing thread with ID 840
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Handshake thread disposed (thread ID: 840)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onIncomingConnectionConnected: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Exiting thread (ID: 840)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnected: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 A3-1]
,D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7148): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 7148): Entering thread (ID: 841)
I/io.jxcore.node.IncomingSocketThread( 7148): Local host address: localhost/127.0.0.1, port: 37082
D/io.jxcore.node.IncomingSocketThread( 7148): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7148): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7148): Exiting thread (ID: 841)
I/jxcore-log( 7148): 2016-01-08T09:55:54.169Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7148): 
,D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 842, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 843, name: Receiver)
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d35a8 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7148): 2016-01-08T09:55:55.527Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.543Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.555Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.558Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.561Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.564Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.645Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.667Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.693Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.761Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.769Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.774Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.777Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.815Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.905Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.918Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.925Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.934Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.938Z SendDataTCPServer.js: TCP/IP server has received 32670 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:55.974Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:55.978Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 7148): 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7148): 2016-01-08T09:55:56.061Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.076Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:56.115Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.206Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 7148): 
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=167 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001080a436f72646f7661703270c00c000c01
,I/jxcore-log( 7148): 2016-01-08T09:55:56.258Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:56.365Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.404Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.439Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.474Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.529Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.549Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.565Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.577Z SendDataTCPServer.js: TCP/IP server has received 82170 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:56.613Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.670Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.680Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data,
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:56.684Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:56.688Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.724Z SendDataTCPServer.js: TCP/IP server has received 99990 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:55:56.727Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7148): 
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d33e0 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-btm  ( 3818): BTM: Local device role : 0x00
W/bt-btm  ( 3818): BTM: RemBdAddr: 08eca9507541
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btif ( 3818): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 843, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7148): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 841
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 843
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 842
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local input stream...
W/bt-btm  ( 3818): BTM_SwitchRole BDA: f4-f1-e1-5c-3b-e2,
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 842, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7148): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed,
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7148): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 843, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 842, name: Sender)
I/jxcore-log( 7148): 2016-01-08T09:55:57.200Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7148): 
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d35a8 rs_disc_pending=1
E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
D/WifiServerServiceExt( 1036): Connected BT device : -3
I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
W/bt-rfcomm( 3818): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x0048
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-rfcomm( 3818): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=168 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7148): 2016-01-08T09:55:58.105Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:55:58.106Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5,a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/btif_config_util( 3818): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=170 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=171 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=172 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010c000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010c000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=173 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010c000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=174 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=908086202, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{169fa839 type 2 when 550021 android} when 550021
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=908086202 [*alarm*], flags=0x0
,I/BooksSync( 6997): Starting books sync
,D/BooksSync( 6997): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=175 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3625689868574461857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -4
,I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=176 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=177 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=179 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  se,condary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManag,er( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 66172(3MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 3.295ms total 162.308ms
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:56:03.112Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:03.113Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:03.113Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:03.114Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
,D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 7148): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7148): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3625689868574461857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=180 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6997): Authentication error
E/BooksAccountManager( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6997): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1691046e V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=181 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ApiaryClient( 6997): Error response from books API: {
W/ApiaryClient( 6997):  "error": {
W/ApiaryClient( 6997):   "errors": [
W/ApiaryClient( 6997):    {
W/ApiaryClient( 6997):     "domain": "global",
W/ApiaryClient( 6997):     "reason": "required",
W/ApiaryClient( 6997):     "message": "Login Required",
W/ApiaryClient( 6997):     "locationType": "header",
W/ApiaryClient( 6997):     "location": "Authorization"
W/ApiaryClient( 6997):    }
W/ApiaryClient( 6997):   ],
W/ApiaryClient( 6997):   "code": 401,
W/ApiaryClient( 6997):   "message": "Login Required"
W/ApiaryClient( 6997):  }
W/ApiaryClient( 6997): }
,W/ApiaryClient( 6997): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3625689868574461857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6997): Headers:
W/ApiaryClient( 6997): accept-encoding: [gzip]
W/ApiaryClient( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6997): gdata-version: 2
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=182 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/BooksSync( 6997): Soft error: 
E/BooksSync( 6997): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3625689868574461857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6997): Headers:
E/BooksSync( 6997): accept-encoding: [gzip]
E/BooksSync( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6997): gdata-version: 2
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6997): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6997): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6997): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6997): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6997): {
E/BooksSync( 6997):  "error": {
E/BooksSync( 6997):   "errors": [
E/BooksSync( 6997):    {
E/BooksSync( 6997):     "domain": "global",
E/BooksSync( 6997):     "reason": "required",
E/BooksSync( 6997):     "message": "Login Required",
E/BooksSync( 6997):     "locationType": "header",
E/BooksSync( 6997):     "location": "Authorization"
E/BooksSync( 6997):    }
E/BooksSync( 6997):   ],
E/BooksSync( 6997):   "code": 401,
E/BooksSync( 6997):   "message": "Login Required"
E/BooksSync( 6997):  }
E/BooksSync( 6997): }
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6997): 	... 8 more
,E/BooksSync( 6997): Sync error
E/BooksSync( 6997): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6997): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3625689868574461857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6997): Headers:
E/BooksSync( 6997): accept-encoding: [gzip]
E/BooksSync( 6997): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6997): gdata-version: 2
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6997): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6997): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6997): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6997): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6997): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6997): {
E/BooksSync( 6997):  "error": {
E/BooksSync( 6997):   "errors": [
E/BooksSync( 6997):    {
E/BooksSync( 6997):     "domain": "global",
E/BooksSync( 6997):     "reason": "required",
E/BooksSync( 6997):     "message": "Login Required",
E/BooksSync( 6997):     "locationType": "header",
E/BooksSync( 6997):     "location": "Authorization"
E/BooksSync( 6997):    }
E/BooksSync( 6997):   ],
E/BooksSync( 6997):   "code": 401,
E/BooksSync( 6997):   "message": "Login Required"
E/BooksSync( 6997):  }
E/BooksSync( 6997): }
E/BooksSync( 6997): 
E/BooksSync( 6997): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6997): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6997): 	... 8 more
I/BooksSync( 6997): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550021, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=183 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=184 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 557509822499; DSPS: 18409408; Offset : -4315833932
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=185 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=187 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=188 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=189 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=190 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=191 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=192 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=193 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=194 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=195 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3818): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=8 link_role=0  transport=1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): l2c_link_hci_conn_req:current link_role= 0
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3818): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
D/WifiServerServiceExt( 1036): Connected BT device : -3
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: f4-f1-e1-5c-3b-e2
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x004c,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x004c,PSM: 1,peer MTU present: 0,peer MTU: 256
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0049
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 13
W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 7
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x004d,PSM: 1,our MTU present:1,our MTU:672
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 0
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x004d,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x004a
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 14
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 844)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/bt-btm  ( 3818): btm_acl_created hci_handle=7 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=7 link_role=0  transport=1
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3818): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
D/WifiServerServiceExt( 1036): Connected BT device : -2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 844)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
I/jxcore-log( 7148): 2016-01-08T09:56:16.540Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:16.540Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:16.541Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/WifiNative-p2p0( 1036):    returned b60376a0
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 844)
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=196 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 2
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-34-8a-a0
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: S5-1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x004b  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x004b,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x004b,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x004b
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3818): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): L2CA_ErtmConnectRsp()  CID: 0x004c  Result: 0  Status: 0  BDA: 7cf90e348aa0  p_ertm_info:0x00000000
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x004c,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x004c,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255
W/bt-btif ( 3818): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3818): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3818): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Incoming connection initialized (thread ID: 846)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Entering thread (ID: 846)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesRead: Read 63 bytes successfully (thread ID: 846)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): onBytesWritten: 63 bytes successfully written (thread ID: 846)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): removeThreadFromList: Removing thread with ID 846
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Handshake thread disposed (thread ID: 846)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7148): Exiting thread (ID: 846)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 S5-1]
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7148): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7148): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 7148): Entering thread (ID: 847)
,I/io.jxcore.node.IncomingSocketThread( 7148): Local host address: localhost/127.0.0.1, port: 37082
D/io.jxcore.node.IncomingSocketThread( 7148): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7148): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7148): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7148): Exiting thread (ID: 847)
I/jxcore-log( 7148): 2016-01-08T09:56:17.344Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7148): 
D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 849, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7148): Entering thread (ID: 848, name: Sender)
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=197 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
,E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d35a8 rs_disc_pending=0,
W/bt-btif ( 3818): bta_dm_check_av:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=198 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/jxcore-log( 7148): 2016-01-08T09:56:18.845Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:18.861Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:18.909Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:18.923Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.051Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.159Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.262Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.362Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.370Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.445Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.460Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:19.471Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.503Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.510Z SendDataTCPServer.js: TCP/IP server has received 21062 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:19.543Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.603Z SendDataTCPServer.js: TCP/IP server has received 27002 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.614Z SendDataTCPServer.js: TCP/IP server has received 28982 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.624Z SendDataTCPServer.js: TCP/IP server has received 30962 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.637Z SendDataTCPServer.js: TCP/IP server has received 32942 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.676Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.691Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:19.697Z SendDataTCPServer.js: TCP/IP server has received 42842 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.749Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.900Z SendDataTCPServer.js: TCP/IP server has received 44822 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.966Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:19.980Z SendDataTCPServer.js: TCP/IP server has received 48782 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.052Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.205Z SendDataTCPServer.js: TCP/IP server has received 50762 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.225Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.253Z SendDataTCPServer.js: TCP/IP server has received 52742 bytes of data
I/jxcore-log( 7148): 
,E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1036): Connected BT device : -3
I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
,I/jxcore-log( 7148): 2016-01-08T09:56:20.278Z SendDataTCPServer.js: TCP/IP server has received 54722 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.282Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.287Z SendDataTCPServer.js: TCP/IP server has received 56702 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.289Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 7148): 
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
I/jxcore-log( 7148): 2016-01-08T09:56:20.346Z SendDataTCPServer.js: TCP/IP server has received 58682 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.351Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.358Z SendDataTCPServer.js: TCP/IP server has received 60662 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.366Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.404Z SendDataTCPServer.js: TCP/IP server has received 62642 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.412Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.414Z SendDataTCPServer.js: TCP/IP server has received 64622 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.433Z SendDataTCPServer.js: TCP/IP server has received 66602 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.497Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.511Z SendDataTCPServer.js: TCP/IP server has received 70562 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.519Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.524Z SendDataTCPServer.js: TCP/IP server has received 72542 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.554Z SendDataTCPServer.js: TCP/IP server has received 76502 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.561Z SendDataTCPServer.js: TCP/IP server has received 78482 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.564Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.569Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.577Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.615Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.648Z SendDataTCPServer.js: TCP/IP server has received 86402 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.657Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.660Z SendDataTCPServer.js: TCP/IP server has received 88382 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.665Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.674Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.679Z SendDataTCPServer.js: TCP/IP server has received 92342 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.719Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:20.734Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:20.736Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7148): 
,W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3818): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 849, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7148): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 847
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 849
D/io.jxcore.node.IncomingSocketThread( 7148): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7148): doStop: Thread ID: 848
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local input stream...
W/bt-rfcomm( 3818): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-l2cap( 3818): L2CA_DisconnectRsp()  CID: 0x004c
W/bt-l2cap( 3818): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
W/bt-rfcomm( 3818): RFCOMM_DisconnectInd LCID:0x4c
W/io.jxcore.node.StreamCopyingThread( 7148): Either failed to read from the output stream or write to the input stream (thread ID: 848, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7148): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7148): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 7148): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7148): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 848, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 7148): Exiting thread (ID: 849, name: Receiver)
I/jxcore-log( 7148): 2016-01-08T09:56:20.822Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7148): 
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d3050 rs_disc_pending=0
W/bt-btif ( 3818): bta_dm_check_av:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3818): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,I/jxcore-log( 7148): 2016-01-08T09:56:21.542Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:21.543Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,D/btif_config_util( 3818): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=199 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -4
,I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=200 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=201 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=202 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add,/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:56:26.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:26.548Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:26.548Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:26.549Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 7148): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 850)
,W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=203 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=204 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=205 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
,W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 577516366762; DSPS: 19064982; Offset : -4315822044
W/bt-btm  ( 3818): btm_acl_created hci_handle=9 link_role=1  transport=1
W/bt-btm  ( 3818): btm_acl_created hci_handle=9 link_role=1  transport=1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3818): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,D/WifiServerServiceExt( 1036): Connected BT device : -3
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x004d,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x004d,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: f4-f1-e1-5c-3b-e2
W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x004d
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 16
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 850)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 850)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 850)
I/jxcore-log( 7148): 2016-01-08T09:56:27.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:27.993Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:27.993Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 850)
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{367fb2db type 2 when 580112 android} when 580112
,E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -4
,I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7148): 2016-01-08T09:56:32.994Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:32.995Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=206 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/btif_config_util( 3818): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=207 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=208 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=209 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=210 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=211 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=212 dispatchEvent: P2P-SERV-DISC-REQ 2462 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 7 1200010d0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 7 1200010d0a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 ee:1f:72:18:8b:78 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:56:38.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:38.001Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:38.001Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): 2016-01-08T09:56:38.017Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
,I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 7148): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 852)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7148): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=214 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=215 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=216 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=217 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=218 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=219 dispatchEvent: P2P: Reject scan trigger since one is already pending
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3818): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3818): invalid rfc slot id: 17
,W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 597518408161; DSPS: 19720409; Offset : -4315825271
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=220 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=221 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=222 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler, }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7148): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3818): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 852)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 852)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 852)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 7148): 2016-01-08T09:56:51.019Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:51.020Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:51.020Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 852)
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=224 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001100a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=225 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=226 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7148): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=227 dispatchEvent: P2P-SERV-DISC-REQ 2462 7e:f9:0e:37:96:ac 0 7 1200010a0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 7 120001100a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 7 120001100a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=228 dispatchEvent: P2P-SERV-DISC-REQ 2462 a2:39:f7:70:12:80 0 7 120001100a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=229 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=230 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED ,
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=231 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=232 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=233 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=234 dispatchEvent: P2P-SERV-DISC-REQ 2462 a2:39:f7:6f:c9:5d 0 8 1200010f0a436f72646f7661703270c00c000c01
I/jxcore-log( 7148): 2016-01-08T09:56:56.023Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:56:56.024Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=235 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=236 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=237 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=238 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=239 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=240 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplican,t( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=241 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:57:01.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:01.029Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:01.029Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:01.030Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 7148): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 854)
,W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: f4f1e15c3be2  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=242 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2,
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=243 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=244 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=245 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=246 dispatchEvent: P2P-SERV-DISC-REQ 2462 92:b6:86:43:73:1c 0 7 1200010c0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=247 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=248 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 617519930288; DSPS: 20375819; Offset : -4315829075
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=249 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=250 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=251 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=252 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=253 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=254 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001110a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=255 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=256 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1966): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000111000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000111000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=257 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000111000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7148): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7148): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionTimeout: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 7148): 2016-01-08T09:57:16.062Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:16.084Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 7148): 
I/jxcore-log( 7148): oneRoundDownNow
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:16.086Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7148): 
D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:57:16.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 7148): 
I/jxcore-log( 7148): ---- round done--------
I/jxcore-log( 7148): 
I/jxcore-log( 7148): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): startWithNextDevice
I/jxcore-log( 7148): 
I/jxcore-log( 7148): do fake peer & start
I/jxcore-log( 7148): 
I/jxcore-log( 7148): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:16.099Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:16.099Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:16.099Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7148): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): connect: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7148): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 7148): timeout now
I/jxcore-log( 7148): 
I/jxcore-log( 7148): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 7148): 
I/jxcore-log( 7148): sendReportNow
I/jxcore-log( 7148): 
I/jxcore-log( 7148): done, now sending data to server
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 856)
,W/LGMDMUISystemServiceAdapter( 7148): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7148): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3818): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/LGBluetoothServiceAdapter( 3818): [BTUI] connectSocket FD=86 mFd=85
I/jxcore-log( 7148): 2016-01-08T09:57:16.124Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7148): 
D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:57:16.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3818): btm_acl_created hci_handle=11 link_role=1  transport=1
,W/bt-btm  ( 3818): btm_acl_created hci_handle=11 link_role=1  transport=1
W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3818): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-l2cap( 3818): l2c_link_hci_conn_req:current link_role= 0
W/bt-btif ( 3818): info:x10
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3818): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
W/bt-btm  ( 3818): btm_read_remote_version_complete: BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,D/WifiServerServiceExt( 1036): Connected BT device : -3
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-btm  ( 3818): btm_process_remote_ext_features_page 0: BDA: f4-f1-e1-5c-3b-e2
,W/bt-btm  ( 3818): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 3818): btm_process_remote_ext_features_page 1: BDA: f4-f1-e1-5c-3b-e2
W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3818): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0048,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3818): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3818): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0048,PSM: 1,peer MTU present: 0,peer MTU: 256
W/bt-sdp  ( 3818): process_service_search_attr_rsp
W/bt-l2cap( 3818): L2CA_DisconnectReq()  CID: 0x0040
,W/bt-l2cap( 3818): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
W/bt-l2cap( 3818): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3818): BTM_SwitchRole BDA: f4-f1-e1-5c-3b-e2
W/bt-btm  ( 3818): Requested New Role: 0
W/bt-btif ( 3818): invalid rfc slot id: 19
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 854)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 854)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 854)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 854)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
W/bt-btm  ( 3818): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=258 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=259 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=260 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3818): btm_acl_role_changed: BDA: f4-f1-e1-5c-3b-e2
,W/bt-btm  ( 3818): btm_acl_role_changed: New role: 1
W/bt-btm  ( 3818): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3818): tBTM_SEC_DEV:0xa03d35a8 rs_disc_pending=2
E/bt-btm  ( 3818): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3818): bta_dm_check_av:0
W/bt-l2cap( 3818): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3818): btif_dm_cback : unhandled event (14)
,D/WifiServerServiceExt( 1036): Connected BT device : -4
I/BluetoothMapService( 3818): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3818): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3818): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3818): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3818): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3818): state: -2147483648
D/LGBluetoothPowerSaveListener( 7226): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4611): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4611): Bluetooth Device Name: XT1039
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=261 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=262 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/btif_config_util( 3818): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3818): L2CAP - st: CLOSED evt: 1
,W/bt-sdp  ( 3818): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3818): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3818): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 856)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Maximum number of allowed retries (0) reached, giving up... (thread ID: 856)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): Exiting thread (thread ID: 856)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7148): shutdown (thread ID: 856)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 HTC One M8s]
I/jxcore-log( 7148): 2016-01-08T09:57:27.261Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 HTC One M8s] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:27.261Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 HTC One M8s] failed
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:27.266Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 637532228250; DSPS: 21031582; Offset : -4315829802
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=263 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=264 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=265 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=266 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2728): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ wh,en=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7148): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service request added successfully
I/wpa_supplicant( 2728): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1966): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=267 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001120a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2728): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=268 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1966): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service discovery started successfully
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2728): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1966): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=269 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=270 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1966): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7148): teardown
I/jxcore-log( 7148): 
,D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 7148): testSendData stopped
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7148): onServerStopped
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7148): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7148): setState: NOT_STARTED
I/jxcore-log( 7148): StopBroadcasting went ok
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:31.722Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7148): 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/io.jxcore.node.ConnectionHelper( 7148): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7148): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7148): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7148): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139268 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2728): P2P-FIND-STOPPED 
D/WfdsMonitor( 1966): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=271 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7148): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1036): InactiveState{ when=-19ms what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-19ms what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): remove channel information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7148): Service requests cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/jxcore-log( 7148): 2016-01-08T09:57:32.267Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:32.268Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): ****TEST TOOK:  ms ****
I/jxcore-log( 7148): 
,I/jxcore-log( 7148): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7148): 
,D/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7148): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7148): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 7148): 2016-01-08T09:57:37.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:37.282Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:37.284Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:37.285Z SendDataConnector.js: do connect now
I/jxcore-log( 7148): 
I/io.jxcore.node.ConnectionHelper( 7148): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7148): connect: Not running, please call start() first
I/jxcore-log( 7148): 2016-01-08T09:57:37.288Z SendDataConnector.js: CLIENT connected to -1, error: Not running, please call start() first
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:37.289Z SendDataConnector.js: CLIENT Can not Connect: Not running, please call start() first
I/jxcore-log( 7148): 
I/jxcore-log( 7148): 2016-01-08T09:57:37.290Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7148): 
,D/AndroidRuntime( 7868): 
D/AndroidRuntime( 7868): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7868): CheckJNI is OFF
D/AndroidRuntime( 7868): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1036): Killing 7148:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1036): WIN DEATH: Window{2d6b9c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1036): Client connection lost with reason: 4
D/InputDispatcher( 1036): Window went away: Window{2d6b9c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{3f5e49c7 u0 com.test.thalitest/.MainActivity t4}
,W/PackageSettings( 1036): Skipping PackageSetting{2efb0dbe com.example.hello/10319} due to missing metadata
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
W/ActivityManager( 1036): Spurious death for ProcessRecord{d401178 7148:com.test.thalitest/u0a311}, curProc for 7148: null
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{3f5e49c7 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{3f5e49c7 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2086): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2086): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{2a26ab56 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{152f57d7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=908086202, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
I/art     ( 4611): Explicit concurrent mark sweep GC freed 33229(1647KB) AllocSpace objects, 4(64KB) LOS objects, 34% free, 30MB/46MB, paused 295us total 40.171ms
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3737): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,W/System.err( 4557): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4557): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4557): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4557): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4557): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4557): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4557): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4557): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4557): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4557): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1931): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3737): handleMessage: what(1000) actionID(0x1000003)
D/PostponalbeReceiver( 6669): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1036): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7901 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2086): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2086): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2086): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1931): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3737): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
I/[SystemUI]QSlideListController( 1458): onReceive = android.intent.action.PACKAGE_REMOVED
,V/BoardContentProvider( 3737): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2086): , create_time: 1430558575574
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2086): , create_time: 1430558575600
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2086): , create_time: 1452175675684
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
D/WallpaperManager( 2086): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d1afa62,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1897): split_name #11 / not available #0
,D/SplitUIService( 1897): removed split : 
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1458): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1897): split_name #11 / not available #0
I/SplitUIService( 1897): split app #11
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
I/art     ( 1036): Explicit concurrent mark sweep GC freed 38305(2MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.425ms total 230.002ms
,I/[LGHome]EVENT( 2086): [Launcher.java:5349:onStop()]onStop
I/art     ( 1036): WaitForGcToComplete blocked for 120.327ms for cause Explicit
I/LockScreenSettings( 7901): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/AppUp4:PreloadHelper( 7367): added Exclude : com.test.thalitest
,W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] [-] updateMediaPlayerInfo
I/ThermalEngine(  324): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3155): Thermal-Lib-Client: Client request sent
,I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7923 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
D/administrator( 1036): Handling package changes for user 0
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{6db7a71 u0 com.lge.launcher2/.Launcher t3} time:648010
D/KeyguardModel( 1458): handleShortcutListChanged...
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
I/[Concierge]WidgetView( 2086): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/[Concierge]Service( 2616): onStartCommand(). Type : 8
D/[Concierge]Service( 2616): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2616): Update widget ID : 11
D/[Concierge]WidgetView( 2086): change position of spinner
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
,I/[Concierge]WidgetView( 2086): initWebView(). Time : 1452247058303
D/[Concierge]Service( 2616): onStartCommand(). Type : 0
I/ActivityManager( 1036): Killing 6251:com.android.vending/u0a44 (adj 15): empty #17
W/ResourcesManager( 7923): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7923): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7923): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7923): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7923): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 10713(578KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.311ms total 200.451ms
,D/KeyguardModel( 1458): handleShortcutListChanged...
W/libprocessgroup( 1036): failed to open /acct/uid_10044/pid_6251/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
I/[Concierge]WebView( 2086): Return exist ConciergeWebView. Reuse : 180571612
D/[Concierge]WidgetView( 2086): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2086): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@14b1db64
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/SystemConfig( 7923): BUILD Country: EU
I/SystemConfig( 7923): BUILD Operator: OPEN
D/[Concierge]WidgetBroadcastReceiver( 2086): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2086): Widget kill message received. Destory myself. My : 1452246438841, New one : 1452247058303
D/[Concierge]WidgetView( 2086): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2086): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/[Concierge]WidgetView( 2086): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1036): Killing 7248:com.lge.sync/1000 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7868): Shutting down VM
,I/Timeline( 2086): Timeline: Activity_idle id: android.os.BinderProxy@2b5a1f1b time:648230
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7248/cgroup.procs: No such file or directory
,I/SystemConfig( 7923): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7923): existFile = false
I/SystemConfig( 7923): canReadFile = false
I/SystemConfig( 7923): systemFeature RCS result false
D/SystemConfig( 7923): refreshRcsSupport() :false
I/PackageChangeReceiver( 6722): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2236): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1036): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7946 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7946): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7946): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7946): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7946): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7946): Total System Memory = 2995761152
I/chromium( 2086): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/SystemHelper( 7946): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1036): Killing 7411:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/GBoardtInterface( 2086): onReloaded()
,I/GBoardWebViewClient( 2086): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2030): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1036): failed to open /acct/uid_10026/pid_7411/cgroup.procs: No such file or directory
,D/LIA_Service_LIAService( 2030): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3737): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6669): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3737): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/CoreEventReceiver( 7714): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1931): notifyUserLog: 1000001
,D/PackageIntentReceiver( 7226): Not supported Hotkey customization function 
D/LIA_Informant_ActionManagerMessageHandler( 3737): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3737): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1931): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3737): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3737): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3737): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3737): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3737): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,D/HideNavigationAppsReceiver( 7226): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7226): replacing : false
D/HideNavigationAppsReceiver( 7226): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7226): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7226): replacing : false
,I/UpdateIcingCorporaServi( 4611): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1036): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7967 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,D/DocsApplication( 7967): Installing DEX configuration.
,D/DexInstaller( 7967): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7967): Provided clientMode=RELEASE, packageInfo=PackageInfo{1dd32adc com.google.android.apps.docs}
D/TAG     ( 7967): onCreate()
D/CrossAppStateProvider( 7967): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/UpdateIcingCorporaServi( 4611): UpdateCorporaTask done [took 102 ms] updated apps [took 101 ms] 
,I/GBoardtInterface( 2086): exportHTML()
,I/GBoardtInterface( 2086): exportHTML()

```
